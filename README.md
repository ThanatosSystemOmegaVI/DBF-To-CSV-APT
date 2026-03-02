# dbf-repo
dbf-repo


# install (:bash)

curl -fsSL https://thanatossystemomegavi.github.io/DBF-To-CSV-APT/key.gpg -o /tmp/dbf-reader-key.gpg && sudo gpg --dearmor -o /usr/share/keyrings/dbf-reader.gpg /tmp/dbf-reader-key.gpg && rm /tmp/dbf-reader-key.gpg

sudo sh -c 'echo "deb [signed-by=/usr/share/keyrings/dbf-reader.gpg] https://thanatossystemomegavi.github.io/DBF-To-CSV-APT stable main" > /etc/apt/sources.list.d/dbf-reader.list'

sudo apt update && sudo apt install -y dbf-reader