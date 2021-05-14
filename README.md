# Configuring the `learn-lab` Gem

## Introduction 

As you continue your journey into programming, you will learn to use many tools to make your work easier that you only sort of understand. Node packages, Ruby gems, libraries, command-line applications, frontend frameworks, etc... many of these tools are actually built out of other tools, things you may never have heard of. That is okay.

Thanks to the collective work of many programmers around the world, we're able to tap in to a diverse ecosystem of tools. We don't need to know how they all work together for them to be useful to us. You might one day know JavaScript well enough to build your own version of [React](http://reactjs.org), but you'll be able to use React long before you know how all the parts work. Many of these tools are designed to solve problems so we can focus our energy and time elsewhere.

We've already used a few tools to help us get started with programming. If you recall from the previous installation instructions, we've installed NVM, the Node Version Manager, which manages which version of Node you're using on your computer. We've been using NPM, Node **Package** Manager, to run local tests. We've also been using Git in the command line to interface remotely with GitHub.

In this lesson, we're going to introduce another tool that will help us going forward, the `learn-lab` gem.

## The `learn-lab` Gem

So, if all these tools we use are meant to solve problems, 
what problems does the `learn-lab` gem solve?

Once you've pushed your solution up to GitHub, you then have to submit a link in Canvas. The gem provides one final step. It makes sure you got all your tests to pass before submitting. We will have a new command called `learn-lab test`. This new command will output a token that you should copy paste into the comments field of your submission.

Note: The instructions here assume you've successfully installed Ruby and Node in the previous environment setup instructions.

## Install the `learn-lab` Gem
To install the gem, run the following in your terminal:

`gem install learn-lab`

Before we can use the gem, we'll need to configure it.

## Configure the Gem
### Action Item
1. Open your terminal
1. In your terminal run `learn-lab config`
1. Enter the same email you used for your Canvas login

## Using the `learn-lab` Gem
1) On this assignment's Canvas page, click the Fork button in the upper right corner of the page:

![Fork Button](https://curriculum-content.s3.amazonaws.com/fork-link.png)

You should notice a change in the button's behavior — rather than bringing you to the fork page in GitHub, you'll be redirected to your repository already in the process of being forked.

2) Once your fork is ready, click the Code button and copy the SSH repository info by clicking the clipboard button.

![Clone with SSH](https://curriculum-content.s3.amazonaws.com/canvas-welcome/clone-with-ssh.png)

**_Note_**: Make sure you're choosing **SSH** and not **HTTPS**.

3) In your terminal, navigate to where you'd like to put this repository locally, clone it down and navigate into the folder.

```
git clone git@github.com:/<GITHUB_USER>/macos-env-flatiron-student-portal.git
cd macos-env-flatiron-student-portal
```

4) run npm install got install all of the required packages. Now you can run `learn-lab test`. **Complete Your First Software Engineering Assignment**. By cloning this assignment down, you've already passed the test!

```
This assignment
    ✓ has been correctly cloned to your local environment

  1 passing (5ms) 
```

When all tests are passing, you can head back to the assignment on Canvas. You'll want to commit and push your new code to GitHub. 

Each assignment will be different and will include instructions on what is required to complete it. Some labs will have many tests. You can run `learn-lab test` as many times as you'd like while working to solve these labs. 

## Types of Assignments

For most assignments, you will go through the process we just walked through. In our curriculum, these assignments are often referred to as **labs** — coding lessons that include tests. There are a few other types of assignments, though, that require slightly different submission steps:

- **Code-alongs:** These also require code, but will guide you through what needs to be written. There are no tests to pass, but you will still need to go through forking, cloning, and running learn test. You should see a message stating that no tests were found, but if you check the assignment in Canvas, you should see it is marked as Complete.
- **Portfolio Projects:** For these assignments, you'll be building fully functional applications. Some guidelines and requirements will be provided, but it will be up to you to design and create your own app. These will eventually become the projects you showcase to potential employers! You will submit your projects in Canvas by submitting a link to your GitHub repo.
- **Blog Submissions:** Blogs are a required part of our Software Engineering courses. They help to develop your online presence and are a great way to reinforce the concepts you learn. You'll write your blog posts on a different platform, but submit links to them in Canvas.

## Submitting Assignments

For both portfolio projects and blog posts, you'll need to manually submit a link to your work on Canvas. While viewing the assignment, you should see a **Submit Assignment** button in the upper-right section of the page.

![Submit Assignment Button](https://curriculum-content.s3.amazonaws.com/canvas-welcome/submit-assignment-canvas.png)

Clicking this button will bring you to the bottom of the page where you can submit a GitHub URL link to your work.

![Submit Assignment Form](https://curriculum-content.s3.amazonaws.com/canvas-welcome/submit-assignment-canvas-form.png)

Submit both your GitHub URL **and** the token in the comments provided by `learn-lab test`. Upon submission you should see confetti appear, indicating that your submission has been accepted.

## Conclusion

You've completed your first assignment using the `learn-lab` gem! **Use this style of submitting assignments throughout the course.** Sometimes we mention a learn or learn submit command. This hide too much and we want you to understand what's going on. Follow the following steps for how to submit **every lab**.

- Click the Fork button on the Canvas assignment
- Once the assignment is forked, clone it down to your local machine
- Complete any required work, then run `learn-lab test`
- If all tests pass, you'll be provided a token
- Push your work to GitHub
- Submit the GitHub link as well as the token in the comments to mark an assignment as complete.

Equipped with this knowledge, you are now ready to tackle greater challenges!
