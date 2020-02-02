.PHONY: compile
compile: bin/MUSIC

bin/MUSIC: | $(MUSIC_DIR)
	cp compile/Makefile $(MUSIC_DIR)
	source module-reset.sh && cd $(MUSIC_DIR) && make
	mkdir -p bin
	mv $(MUSIC_DIR)/MUSIC $@
