# shit
*kid gloves for git that keep you out of bad situations*

the intent is to build a shell script that wraps `git` and limits its functionality to only what keeps you in the nice world where everything's all flowing in one direction into a single source of truth, and you're not having to spend two hours googling how to abort a merge while in 'detached HEAD' state. no rebases. basically you can cut branches and merge them into main, and you can pull in updates. maybe merge conflicts will be easier to deal with somehow too, like your only options are "yours" or "theirs".

yeah this all makes `shit` unsuitable for serious business but if you need to do something really cool, you can always drop down into `git` and do it! the point of `shit` is to give regular people who want a version control system something easy to use. and are also happy using a command line interface. if they exist. if they don't, well i am a professional software developer and if it ends up good i'll probably use it most of the time too just for the guarantee that it will keep me out of trouble!

## contributing

i'm thinking the best way to start out with this is to implement the very basics and then build up. like, what if you can only create a new repo and commit changes on the default branch to begin with, and then add features from there, being careful to only add stuff that doesn't allow big problems to happen.
