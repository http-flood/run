# run

git clone https://github.com/http-flood/run.git

wget https://dl.google.com/go/go1.21.3.linux-amd64.tar.gz
sudo tar -C /usr/local -xzf go1.21.3.linux-amd64.tar.gz

#Add to .profile (or .bash_profile)
export PATH=$PATH:/usr/local/go/bin
. .profile

cd http-flood
go build ruuner.go
