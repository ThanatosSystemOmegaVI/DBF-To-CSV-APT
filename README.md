# dbf-repo
dbf-repo


# install
curl -fsSL https://thanatossystemomegavi.github.io/DBF-To-CSV-APT/key.gpg \
 | sudo gpg --dearmor -o /usr/share/keyrings/dbf-reader.gpg

 ls -l /usr/share/keyrings/dbf-reader.gpg

 echo "deb [signed-by=/usr/share/keyrings/dbf-reader.gpg] https://thanatossystemomegavi.github.io/DBF-To-CSV-APT stable main" \
 | sudo tee /etc/apt/sources.list.d/dbf-reader.list

 sudo apt update
sudo apt install dbf-reader