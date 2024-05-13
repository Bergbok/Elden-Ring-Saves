# Getting Started

> You'll need [git](https://git-scm.com/downloads) installed and configured. <br>
> Feel free to use [my personally created "mule" save](https://github.com/Bergbok/Elden-Ring-Saves/tree/main/save-files/0-Blank-Slate) to create your builds. <br>
> **Saves containing unobtainable/cut-content items will not be accepted.**

1. **Fork the repository**: Start by forking the repository by clicking the button above the "About" section or by using [this link](https://github.com/Bergbok/Elden-Ring-Saves/fork)

2. **Clone your fork**: Clone your fork to your local machine. This allows you to work on the project from your own computer.

    ```bash
    git clone https://github.com/<your-username></your-username>/Elden-Ring-Saves.git
    ```

3. **(Optional) Create a branch**: Before making your changes, create and switch to a new branch. Alternatively, simply commit to the main branch.

    ```bash
    git checkout -b <your-new-branch-name>
    ```

# Making Changes

1. **Make your changes**: <br>
    **a.** Add your save files to the save-files directory. <br>
    > Add a prefix to save containing folders for sorting purposes - if your saves don't fit into existing categories either make up your own or just use "COMMUNITY".<br>
    > Folder name format: `<COLLECTION_PREFIX>-<NUM_IN_CATEGORY>--<SAVE_NAME>`
    
    **b.** Add a entry to the "Showcase" section in the README with:
    > - Screenshots of your characters's status pages 
    > - (Optional): NG+/Journey level
    > - (Optional): Links to related videos
    > - (Optional): Whatever else you want

2. **Commit your changes**: Once you're happy with your changes, commit them to your branch.

    ```bash
    git add .
    git commit -m "Add/modify save (<SAVE_FOLDER_NAME>)"
    ```

3. **Push your changes**: Push your changes to your fork on GitHub.

    ```bash
    git push origin <your-new-branch-name>
    ```

4. **Open a pull request**: Go to your fork and click on the _"Contribute"_ dropdown, then the _"Open pull request"_ button. <br>
You can also open one on [this page](https://github.com/Bergbok/Elden-Ring-Saves/pulls). <br>
I'll look into merging your saves as soon as I have time.

# Cheat Engine Tips

Get the table [here](https://github.com/The-Grand-Archives/Elden-Ring-CT-TGA).

![Useful Options](https://i.imgur.com/BY9XmLO.png)
> Super useful for creating builds, I recommend setting up hotkeys for the NPC menus - it saves a lot of time.

![Playtime Locking](https://i.imgur.com/VUWsV2n.png)
> Locking playtime to 0