## Commit Message : Log 1 : Brainstorming and introspecting.

## Commit Date : 25th October 2022

## Commit changelog :

<table>
    <tr>
        <td>
            <b>S.No.</b>
        </td>
        <td>
            <b>Log Type</b>
        </td>
        <td>
            <b>Log Description</b>
        </td>
        <td>
            <b>Associated Issue</b>
        </td>
    </tr>
    <tr>
        <td>1.</td>
        <td>Brainstorming</td>
        <td>Throwing out ideas on the wall about import resolver</td>
        <td>import_resolver</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>Introspecting</td>
        <td>Introspecting about the loss of productivity and passion and poor focus since the first lockdown and WFH situation.</td>
        <td>personal_life</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>Planning</td>
        <td>A supercharged yet simple task manager in the form of a google sheet</td>
        <td>task_management</td>
    </tr>
</table>

## Commit Description : 

* #### import_resolver : 

Have been working on and off on a simple import/module resolver for python.
The project will automatically resolve local imports and will also automatically create requirements.txt file and update it too as well as downloading the dependencies from that file based on the import statements in the project. There would also be a running file watcher that will look for structure changes or any new references or import statements that are to be resolved.

###### Tasks : 

- [x] Fetch import statements from files
- [x] Create and store project directory structure
- [x] Create requirements.txt file and add external dependencies   
- [ ] File watcher to look for changes in files for any new import statements (Partially done as i've the file watcher code written for another project already, just have to integrate)
- [ ] Distinguish between local and external imports (partially done, as i've written some code for neglecting local packages/modules, and also have to code to create the project structure, just have to fetch all the members per module/package and use the structure object with the members to neglect those imports from being written in requirements.txt)
- [ ] Add comment command to download a specific version of external dependency
- [ ] ==~~Make it possible to be added as an extension to VSCode or other IDEs so that it can be run automatically.~~== (Feature for future release.)


###### Issues : 

1. Integrate the file watcher code from other project in import_resolver.
2. Write code to fetch all members of a (local) module/package.
3. Integrate the structure object reading in the import statement reading code to distinguish between local and external imports.


###### Comments :

==The project is nearing completion and could be finished easily within a weekend, but requires determination and focused work. Continue with the progress and make it happen.==


* #### personal_life :

Productivity has been on an all time low since april of 2020 and the lowest from august 2020. WFH is not for me. Although i'm not the most social person, but going out and discussing stuff with people, or just having the rush as a background noise, helped me be more productive. I think i'm most focused in an environment where people are working alongside me and i can pace around and discuss stuff with them.

It's challenging to do anything productive now a days, and i'm trying my best to get back on the productivity streak to make amazing stuff and make it open source.

###### Tasks :

- [ ] Be consistent in working on your projects.
- [ ] Make it a habbit to write daily commits like this.
- [ ] Start a study schedule to get back in the game of gaining knowledge.

###### Comments : 
==I have not been an ideal client for most of the productivity tools as i try them, use them for some time, and then never use them actively ever again.
Not just that, I've developed some productivity hacks myself, but never stuck to them. Some motivation is needed to get back in the game.==


* #### planning : 
I've grown to like google sheets ever since i was forced to use them at work. With time i've developed a hobby of creating effective and functional sheets for a lot of task management as well as experimentation and data structuring.

Recently for a project i was leading, i created a task manager in google sheets, and i was amazed by how a simple tool like google sheets can boost my productivity.

No need for fancy tools, a plain ol' excel sheet works best.

I've made a copy of that sheet to manage my own projects now. Thinking of adding additional functionality to it so that i can make it a power tool for project management.

###### Tasks : 
- [ ] Figure out how to trigger actions and change values based on certain inputs in a cell


###### Comments : 
This is simply the best and most simple productivity tool i've ever used, and the best part is, i created the format on my own. Will make it more robust and powerful.