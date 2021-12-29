Bootstrap: docker
From: bgruening/galaxy-stable:17.05

%environment

%files
blast_tools.yml $GALAXY_ROOT/tools.yaml

%post
touch galaxy_install.log
install-tools $GALAXY_ROOT/tools.yaml

%startscript
