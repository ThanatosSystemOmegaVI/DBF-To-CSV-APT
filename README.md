# dbf-repo
dbf-repo


# install
curl -fsSL https://ThanatosSystemOmegaVI.github.io/DBF-To-CSV-APT/key.gpg | \
  sudo gpg --dearmor -o /usr/share/keyrings/dbf-reader.gpg

echo "deb [signed-by=/usr/share/keyrings/dbf-reader.gpg] \
https://ThanatosSystemOmegaVI.github.io/DBF-To-CSV-APT stable main" | \
sudo tee /etc/apt/sources.list.d/dbf-reader.list

sudo apt update
sudo apt install dbf-reader