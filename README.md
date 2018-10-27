# fabricTemplate

# install fabric related images and binaries with specific version
curl -sSL https://raw.githubusercontent.com/hyperledger/fabric/master/scripts/bootstrap.sh | bash -s 1.2.0 1.2.0 0.4.8


./bootstrap.sh 1.2.0 1.2.0 0.4.8 -s

Check the fabric binaries path with: which cryptogen
Usually you should put the binaries in the path: /bin, ~/bin/, /usr/bin/