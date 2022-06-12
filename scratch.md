# geofabrik docker cmd
'''
docker run -it --rm --shm-size=1g -e PBF_URL=https://download.geofabrik.de/north-america/us-west-latest.osm.pbf -e REPLICATION_URL=http://download.geofabrik.de/north-america/us-west-updates/ -e IMPORT_WIKIPEDIA=false -e NOMINATIM_PASSWORD=very_secure_password -v nominatim-data:/var/lib/postgresql/12/main -p 8080:8080 --name nominatim mediagis/nominatim:4.0
'''

# jupyter noteboook
docker run -it --rm -p 8888:8888 -v C:\Users\user\sd-crime:/home/jovyan/work jupyter/datascience-notebook:latest
