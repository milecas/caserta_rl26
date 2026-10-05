# Progetto caserta_rl26

## Prerequisiti
- Sistema operativo Ubuntu.
- Docker installato e configurato.

## Avvio
Per costruire l'immagine e avviare il container:
1. `./docker_scripts/docker_build_image.sh ros2_image`
2. `./docker_scripts/docker_run_container.sh` 

## Verifica
Una volta dentro il container, il completamento del Task 2 è stato verificato con:
- `echo $ROS_DISTRO` (output: humble)
- `ros2 pkg list`
- Creazione del file `test_persistence.txt` per verificare il volume condiviso.
