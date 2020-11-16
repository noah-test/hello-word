# hello-word
This is just a test version.
### About issue and PR
Because the repo contains many subprojects (each subproject corresponds to a directory), in order to clarify which subproject the issue or PR pionts to, please add the sub project name before it's title. 

An example is as follows:

mRNN-mLSTM->This is the title of an issue of mRNN-mLSTM

### About downloading the repo
Because the repo is large, we recommend you download only the subdirectory of interest:

SUBDIR=mRNN-mLSTM

svn export https://github.com/huawei-noah/noah-research/trunk/$SUBDIR

If you'd like to submit a pull request, you'll need to clone the repository; we recommend making a shallow clone (without history).

git clone git@github.com:huawei-noah/noah-research.git --depth=1
