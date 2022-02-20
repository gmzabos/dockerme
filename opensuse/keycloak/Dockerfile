FROM opensuse/tumbleweed:latest

RUN zypper install -y wget java-11-openjdk osc shadow sysconfig systemd

RUN cd ~; wget https://download.opensuse.org/repositories/home:/gmzabos/openSUSE_Tumbleweed/x86_64/keycloak-17.0.0-15.1.x86_64.rpm

RUN cd ~; rpm -ivh keycloak-17.0.0-15.1.x86_64.rpm