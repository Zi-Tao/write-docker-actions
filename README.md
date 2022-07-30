# Welcome to your course 🎉

### Getting started

In this repository we will be diving into the world of writing GitHub Actions! I will guide you through the process of writing a custom Docker based GitHub Actions.

You may be asking yourself, "is Docker the only way to create custom GitHub Actions?"

Currently, there are **two** supported ways to create your own GitHub Actions:

- [Docker container actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/about-actions#docker-container-actions)
- [JavaScript actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/about-actions#javascript-actions)

As you can see we aren't necessarily limited to Docker even though it is the focal point for this course.

---

### Creating vs consuming actions

Although we are going to focus on creating and consuming a custom action, in this course we will also be consuming some actions that have been made public to us. Because your workflows will most likely do the same, I found it important to show you where to look for actions that already exist.

After all, for each time we need to reinvent the wheel for our specific use-case there are a handful of times when we are better off using a wheel that's already made!

- The [GitHub Actions Marketplace](https://github.com/marketplace?type=actions) is the primary place to find open-source actions that the community has written and released. Your action, should you choose to release it, could also reside here one day, ready to be consumed by the world!
- The [GitHub Actions Repository](https://github.com/actions) is where you can find actions that are written by GitHub. We will leverage an action named `[checkout](https://github.com/actions/checkout)` from this repository as we go through this course. I'll explain more about what it does when we use it!
- Your repositories may also contain **private actions** and they will most likely be located in the `.github/actions` directory in the root of your repository. **This is the convention we will be using as we learn how to create our own action.**

---

### Using actions and Learning Lab

In other courses, you may have noticed that some behaviors take me longer to respond to than others. In this course, many of the behaviors we'll see demonstrated will be related to our GitHub Actions workflow. Those workflows sometimes take longer to complete, up to several minutes. Don't be concerned if I take a few minutes to respond, or if I respond too quickly. Sometimes, I'll let you know what the workflow will say before it finishes! Please wait for the workflows to finish before moving on to your next step.

If you aren't already familiar, it may be a good idea to go through the [Introduction to GitHub Learning Lab](https://lab.github.com/githubtraining/introduction-to-github).

---

**Please navigate to the open issue in this repository to get started!**

<hr/>

## GitHub Actions: Write Docker container actions

Step 1: [Setup a workflow file](https://github.com/Zi-Tao/write-docker-actions/issues/1)

Step 2: [Edit the current workflow](https://github.com/Zi-Tao/write-docker-actions/pull/2)

Step 3: [Add an action reference to the workflow](https://github.com/Zi-Tao/write-docker-actions/pull/2)

Step 4: [Create the action metadata](https://github.com/Zi-Tao/write-docker-actions/issues/3)

Step 5: [Write the Hello World source code](https://github.com/Zi-Tao/write-docker-actions/pull/4)

Step 6: [Create the action's `Dockerfile`](https://github.com/Zi-Tao/write-docker-actions/pull/4)

Step 7: [Add input parameters to Hello World's metadata](https://github.com/Zi-Tao/write-docker-actions/pull/4)

Step 8: [Use input parameters in the source code](https://github.com/Zi-Tao/write-docker-actions/pull/4)

Step 9: [Use input parameters in the workflow](https://github.com/Zi-Tao/write-docker-actions/pull/4)

Step 10: [Explore your input parameters](https://github.com/Zi-Tao/write-docker-actions/pull/4)

Step 11: [Setting up the next action](https://github.com/Zi-Tao/write-docker-actions/issues/5)

Step 12: [Add metadata to the cat-fats action](https://github.com/Zi-Tao/write-docker-actions/pull/7)

Step 13: [Fetch a cat fact](https://github.com/Zi-Tao/write-docker-actions/pull/7)

Step 14: [Add Python dependencies](https://github.com/Zi-Tao/write-docker-actions/pull/7)

Step 15: [Add the cat-fact `Dockerfile`](https://github.com/Zi-Tao/write-docker-actions/pull/7)

Step 16: [Use the cat-fat action](https://github.com/Zi-Tao/write-docker-actions/pull/7)

Step 17: [Get ready to purr](https://github.com/Zi-Tao/write-docker-actions/pull/7)

Step 18: [Reference the issue-maker action](https://github.com/Zi-Tao/write-docker-actions/issues/8)

Step 19: [Add dependencies for issue-maker action](https://github.com/Zi-Tao/write-docker-actions/pull/9)

Step 20: [Create the issue-maker's action metadata](https://github.com/Zi-Tao/write-docker-actions/pull/9)

Step 21: [Add the issue-maker action's source code](https://github.com/Zi-Tao/write-docker-actions/pull/9)

Step 22: [Add the issue-maker action's `Dockerfile`](https://github.com/Zi-Tao/write-docker-actions/pull/9)
