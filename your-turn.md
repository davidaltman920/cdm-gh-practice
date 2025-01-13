# Your turn!

**Your task: write a very short story about what makes *digital* different**

For this exercise, I'm asking you to work in groups to brainstorm about this phrase from the course title: "digital media." What do those words mean? Rather than try to reason abstractly about it, let's get creative and **start with a story**: a narrative about how going digital changed (or changes) things.

And, to help you practice working with git and GitHub, I'm going to ask you to collaborate by adding one sentence (or short paragraph, if you're fast) at a time, with a separate *commit* for each addition.

To help merge our stories, let's all use forked versions of the same file: [becoming-digital.md](becoming-digital.md).

## Instructions
1. To start, the team anchor (whoever has the most GitHub experience) should **fork this repository,** using the button at the top right of the [repository home page](../..). ![location of fork button in github](img/github-fork-button.png)
2. Everyone else, decide whether you'll also make your own fork or take turns committing to the anchor's.
3. Clone the forked repository.
    - NB: If you clone a forked repo using GH Desktop, it will ask you whether you want to contribute to the original project or your own fork. _Work on your own fork for now; you can always share your work "upstream" later on._
4. Edit [the story](becoming-digital.md). I've already given you an opening: "When the world was only analog," ... How would you continue the sentence? The paragraph?
   - If you're working together, the first person to propose an answer should write it down.
   - After each meaningful "chunk" of text, or each person's turn, **save and commit.** Use a meaningful commit message, i.e. don't accept the default message, like "update files": instead, say *how* you've updated it, e.g. "add bit about live performances".
   - _Everyone should get a chance to write, save, and commit._
5. Once everyone's had a turn (or after a max of 10 minutes working solo), share it back:
    - If you have a single forked repo, you can just **push** your changes without a conflict.
    - If you have several, you have the option to _merge_ your changes by filing a **pull request** (PR): when you're working in a fork, you can't push directly to someone else's copy of the repo – but the repo owner can review what you've sent, and then decide if they want to pull what you're offering. Thus the name! (You're  *requesting* a pull.) For PR instructions, see below.

When your group is done with your story (or if you're just out of time), please file a pull request back to the assignment repo, as follows:

1. Either click "contribute" on the home screen of your forked repo, or go to the "Pull Requests" tab of either repo and click on the "New pull request" button: ![upstream pull request 2](img/github-upstream-pull-request-2.png)
2. Verify that the arrow is pointing from your repo (the "head") back to the destination (the "base"), whether it's the original benmiller314 repo or one of your groupmates' forks: ![upstream pull request 3](img/github-upstream-pull-request-3.png)
3. Write a short description of what you're sending over -- and notice that a single pull request can contain multiple commits, if you want.
4. The owner of the destination repo will get a notification with the proposed changes, and have an opportunity to check whether it's possible to merge – or if there's a conflict.
    - If there *is* a conflict, you can edit the files and push changes to the "head" (source) branch to automatically update the PR.

That's it for sharing "upstream"!

<details><summary>To see what it would look like to pull request within your own project, click here.</summary>
<h3>GH Pull requests as / instead of commits</h3>
The merge and review process just takes you through a series of prompts and buttons; in the middle, you can write back and forth just as you can on the issue queue. Here's how it would look:

<figure><img src="img/github-pull-request-sequence-with-arrows.png" alt="Six panels illustrating the steps in the caption"/>
<figcaption><ol><li>Top left. Instead of committing directly, you have the option to create a new branch and start a pull request.</li><li>Top right. Confirm the branches and direction of the proposed pull, and write a note to your partners about what you're proposing.</li><li>Middle left. GitHub will attempt to find conflicts.</li><li>Middle right. If there are none, your job is simple! Just decide whether to merge. (If there are, I recommend Atom as a tool to resolve them.)</li><li>Bottom left. The merge becomes a new commit in the destination repository, so you get to write a new commit message. Make it meaningful!</li><li>After the merge, you will be prompted to delete the source branch, since its contents are now integrated.</li></ul>
</figure>
</details>

<hr />

<div class="alert alert-info">
<strong>EXT:</strong> All done with the main activity and still have time left? Read the file called <a href="ext--murray--four-affordances.md">ext--murray--four-affordances.md</a>, and follow the prompts inside it.
</div>
