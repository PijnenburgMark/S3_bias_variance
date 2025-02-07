# S3_bias_variance
Jupyter notebook om de Bias-Variance trade-ff uit te leggen voor de studenten AI 3de semester Hogeschool Utrecht.


Op deze Git-repo vind je een jupyter werkboek en nog wat bestanden. 
Clone deze bestanden naar je computer.

Eerst maken we nu een virtual environment aan waarin we de benodigde packages gaan inzetten.
Open hiervoor een terminal, ga naar je git-repo map en tik:
conda env create -f S3.yaml
De installatie kan even duren.
Na installatie activeren we de omgeving met 
conda activate s3

Eventueel kun je aan de slag met het notebook als je jupyter lokaal hebt geïnstalleerd.
Professioneler is het om docker-desktop te installeren.
Na installatie open je een terminal, gaat naar je git-repo map en tikt:
`docker-compose-up -d`
en je docker-comtainer (= mini-omgeving) wordt vanzelf gemaakt!
(om de container weer af te sluiten, tik docker-compose down)

Vervolgens ga je in je browser naar het volgende adres: `localhost:8888`
