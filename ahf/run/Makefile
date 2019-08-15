.PHONY: run
run: data
	./AHF AHF.input

.PHONY: data
data:
	curl -L http://yt-project.org/data/FIRE_M12i_ref11.tar.gz | tar xz

.PHONY: submit
submit: 
	qsub Amiga_profiles.pbs
