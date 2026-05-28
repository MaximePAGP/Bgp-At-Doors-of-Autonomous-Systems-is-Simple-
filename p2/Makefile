up:
	ansible-playbook ./ansible/playbook.yml 

# 	source ./.venv/bin/activate

re:
	make fclean
	make up

stop:
	vagrant halt

reload:
	vagrant reload

fclean:
	k3d cluster delete -a


.PHONY: up re stop reload fclean ansible