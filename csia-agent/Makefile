include /usr/local/share/luggage/luggage.make
TITLE=CSIA_Agent
REVERSE_DOMAIN=no.hioa.csia_agent
PAYLOAD=\
		pack-usr-bin-csia \
		pack-script-postflight

PACKAGE_VERSION=1.2

pack-usr-bin-csia: l_usr_bin
	@sudo mkdir -p ${WORK_D}/usr/bin
	@sudo ${CP} csia ${WORK_D}/usr/bin/
	@sudo chown root:wheel ${WORK_D}/usr/bin/csia
	@sudo chmod 755 ${WORK_D}/usr/bin/csia

