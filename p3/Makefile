up:
	ansible-playbook ./ansible/playbook.yml 

configs:
	ansible-playbook ./ansible/configs.yml

dockerfiles:
	ansible-playbook ./ansible/dockerfiles.yml

# 	source ./.venv/bin/activate

re:
	make fclean
	make dockerfiles

fclean:
	docker system prune -a -f --volumes


.PHONY: up re fclean configs dockerfiles