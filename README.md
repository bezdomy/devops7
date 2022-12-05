hometask7

1 :
ssh -D8877 -p 4322 root@yoko.ukrtux.com


2 :
python3 -m http.server 8877

ssh -R 14322:localhost:8877 -p root@yoko.ukrtux.com