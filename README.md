# requirments_env_to_docker_image

#for requirmentx.txt

pip freeze | cut -d'=' -f1 > req.txt
