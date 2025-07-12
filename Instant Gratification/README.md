# OVERVIEW

## Kaggle LINK

## Description
Welcome to Instant (well, almost) Gratification!

In 2015, Kaggle introduced Kernels as a resource to competition participants. It was a controversial decision to add a code-sharing tool to a competitive coding space. We thought it was important to make Kaggle more than a place where competitions are solved behind closed digital doors. Since then, Kernels has grown from its infancy--essentially a blinking cursor in a docker container--into its teenage years. We now have more compute, longer runtimes, better datasets, GPUs, and an improved interface.

We have iterated and tested several Kernels-only (KO) competition formats with a true holdout test set, in particular deploying them when we would have otherwise substituted a two-stage competition. However, the experience of submitting to a Kernels-only competition has typically been asynchronous and imperfect; participants wait many days after a competition has concluded for their selected Kernels to be rerun on the holdout test dataset, the leaderboard updated, and the winners announced. This flow causes heartbreak to participants whose Kernels fail on the unseen test set, leaving them with no way to correct tiny errors that spoil months of hard work.

##Say Hello to Synchronous KO
We're now pleased to announce general support for a synchronous Kernels-only format. When you submit from a Kernel, Kaggle will run the code against both the public test set and private test set in real time. This small-but-substantial tweak improves the experience for participants, the host, and Kaggle:

- With a truly withheld test set, we are practicing proper, rigorous machine learning.
- We will be able to offer more varieties of competitions and intend to run many fewer confusing two-stage competitions.
- You will be able to see if your code runs successfully on the withheld test set and have the leeway to intervene if it fails.
- We will run all submissions against the private data, not just selected ones. Participants will get the complete and familiar public/private scores available in a traditional competition.
- The final leaderboard can be released at the end of the competition, without the delay of rerunning Kernels.

This competition is a low-stakes, trial-run introduction to our new synchronous KO implementation. We want to test that the process goes smoothly and gather feedback on your experiences. While it may feel like a normal KO competition, there are complicated new mechanics in play, such as the selection logic of Kernels that are still running when the deadline passes.

Since the competition also presents an authentic machine learning problem, it will also award Kaggle medals and points. Have fun, good luck, and welcome to the world of synchronous Kernels competitions!

## Evaluation
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

## Submission File
For each id in the test set, you must predict a probability for the target variable. The file should contain a header and have the following format:

'''
id,target
ba88c155ba898fc8b5099893036ef205,0.5
7cbab5cea99169139e7e6d8ff74ebb77,0.5
7baaf361537fbd8a1aaa2c97a6d4ccc7,0.5
etc.
'''
