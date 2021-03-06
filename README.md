# Setu in 100 Days of Feature Request

We are so excited to have Setu in the first edition of 100 Days of Feature Request. This is the offcial repository of brand Setu for 100 Days of Feature Request, where you will be able to submit your Pull Request regarding any new feature as a contribution for the contest.

# About the Brand

Setu is a nutrition company that uses industry-leading science to solve real-life problems. #SupplementsThatMakeSense 

Our approach to nutrition is based on a simple truth: science needs to be practical in order to be effective. All our products are backed by heavy-duty R&D, but that would mean little if they didn't actually help real people solve real problems. Being healthy is hard enough already. Science needs a personal touch. That’s why we make supplements that make sense.

# Problem Statements

## Statement No. 1

- **Details** - We are looking to design a system that captures, organizes, and routes data so that it can be used to gain insights. The architecture should organize data/user events to make reporting, analysis, and using data easier.
- **Outcome** - This should help us to get insights into functional areas like target customer behavior, robotic process automation, customer journeys, and user experiences. We’re not looking for some open tools suggestions instead building our own data pipeline. The dashboard should be easy to use.

## Statement No. 2

- **Details** - Setu have a scientifically designed sense test where we ask around 15-20 questions depending on the goal user selects and after considering user inputs, we recommend the best products (2-3 products for each goal) to help achieve your goals. Instead of recommending multiple products, we want to recommend a pill pack that will consist of one pill from each product. So instead of sending 3 product bottles for 1 month,  there will be 30 pill packs and each pack will have 2-3 tablets depending on the recommendation.

- **Outcome** - You have to build this logic on the fly after the user takes the sense test. Few points to be noted:

1. These pill packs will be dispatched from a different warehouse
2. It will depend on the availability of the pill packs, if not available then we’ll recommend the individual products only, else recommend the pill pack.
3. We might need to make the design changes on the result page.
4. How the order creation will happen differently and how you will push this information to the warehouse.

You can find the same problem statements as **issues**. <b>Read the issues and mention them while submitting a Pull Request.</b>

# Rewards

Setu will award some of the great contributions with the following perks:

- Top Contributors receive **Setu Wellness Kit** (Worth 2500 Rs) and **Echo Dot** with opportunities to get hired for Frontend, Backend & Fullstack Developers.
- Cash rewards upto **INR 20K** and get a chance to **join Setu India Team**.

# Table of Contest

* [Contributing](#contributing)
     * [Getting Started](#getting-started)
     * [Submission Guide](#submission-guide)
     * [Creating Pull Requests](#creating-pull-requests)
     * [Commenting on Pull Requests](#commenting-on-pull-requests)
     * [Labelling Pull Requests](#labelling-pull-requests)
     * [Reviewing Pull Requests](#reviewing-pull-requests)
* [Building and Validating](#building-and-validating)

## Contributing

### Getting Started

To get started with the contribution in the Setu repository, simply fork it into your local GitHub account. Make the changes in the forked repository. In this case, the change will be related to the feature that you will be putting in. You can also clone the repository first, and then fork and push it along with the changes. This will also raise a PR.

**Note**: <b>Please be aware that Setu will not share any codebase for this challenge. You are free to develop your own solution using your creativity and imagination (Like that in a hackathon). But, you have to keep the problem statament in mind while developing a solution.</b>

### Submission Guide

To make a submission for the brand Setu in 100 Days of Feature Request, as a first step, fork the repository by clicking the fork button at the right hand corner. In the forked repository, you will be able to make changes and upload your code regarding the feature that you will be making and contributing. 

In the forked repository, create a folder and in that folder, add all the required codes and documents needed for the feature. The folder name should contain your name and the name of the feature which you have built. After naming the folder and later on adding and uploading the contents inside the folder, you will be ready to raise a pull request.

**In the folder, you must have to make a README.md file which will have a detailed description about the feature solution.**

When you are raising a Pull Request, keep in mind to give a proper title of the PR which will be relevant to the changes. In the description section, give a proper description that will tell the summary of the feature request that you have built. Also, you can use markdown in the description that will help you to embed any link or add anything relevant with the description.

### Creating Pull Requests

1. When you're ready to submit your changes, add a descriptive title and comments to summarize the changes made.
2. Select **Create a new branch for this commit and start a pull request**.
3. Check the **Propose file change** button.
4. Scroll down to compare changes with the original document.
5. Select **Create pull request**. 

### Commenting on Pull Requests

Once a pull request is submitted, multiple committers may comment on it and provide edits or suggestions which you can commit directly. You can also add line comments. Take a look at [Commenting on pull requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request) for more details.

### Labelling Pull Requests

A raised Pull Request will be labelled according to the work that has been done in the Pull Request. There are several labels to determine the work that is on-going with the Pull Request. For example, we requested a change in the pull request from the submitter, then the PR will be labelled as *awaiting submitter action*. 

### Reviewing Pull Requests

The Pull Requests will be reviewed on a first come first serve basis. The community and product team of SAWO Labs will be responsible for the reviewing of Pull Requests. Keep in mind that spams will not be tolerated. 

While reviewing the Pull Requests, we may contact the submitter of the PR regarding any changes that need to be made. If the submitter doesn't respond even after making several calls, then we will be forced to close the PR by labelling it as *incomplete*.

Once the review process is complete, the change is either merged into master and pushed immediately or merged into the release branch and pushed in alignment with the release. The branch is then deleted.

## Building and Validating

If you've downloaded the repository and are making a feature on your local machine, you can generate the HTML files from markdown. You can review your changes before you commit them or create pull requests.

**Note:** Commands can be executed on Linux, Mac, and Windows (using Powershell).

1. Open a terminal window, then clone a forked copy of the Setu repository by running the following command::
```sh
https://github.com/Sawo-Community/Setu.git
```
2. Install [pipenv](https://docs.pipenv.org/) by using one of the following commands based on your operating system:

For Mac users where Homebrew is installed:
```sh
brew install pipenv  
```
For other operating systems
```python
pip install pipenv 
```

