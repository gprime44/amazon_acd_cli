FROM openjdk:7

RUN apt-get update && apt-get install -y \
python3 \
python3-appdirs \
python3-dateutil \
python3-requests \
python3-sqlalchemy \
python3-pip \
git \
encfs \
unionfs-fuse \
maven

RUN pip3 install --upgrade git+https://github.com/yadayada/acd_cli.git