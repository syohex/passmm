################################################################################
NAME = passmm
include elpkg/elpkg.mk

################################################################################
all: README.md

################################################################################
README.md: $(CORE_FILE)
	echo '# Passmm: '`$(ELPKG)/desc.sh $(CORE_FILE)`  > $@
	echo                                             >> $@
	$(ELPKG)/fdoc2md.sh passmm-mode $(CORE_FILE)     >> $@
