vanda e-ð, icelandic: "do sth with great care"

# vanda

vanda helps you run computation jobs in an organized way.

vanda was born out of chaos whilest doing research (on chaos).
It is the antidote to having computation results all over the place
and the code that generated them not reasonably version controlled.

The idea is: Keep the code in a git repository and use vanda to start
computation jobs (either directly on another/the same machine or submitted to a
cluster).
vanda links the results to the working directory and notes how they were
generated (specifically, from which git commit).
Computation results can thus be easily managed and reproduced.

## workflow

	# write some code and define how to run it
	vim computation_code.py
	vim vanda_job.sh

	# keep the code version controlled
	git add *
	git commit -a
	git push

	# run a job for the current commit
	vanda run

	# find results of the job conveniently
	ls vj20200202_133700

