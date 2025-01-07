## KULKAN EKOPARTY 2024 CTF CHALLENGE - NMAP RCE

A challenge we made for Ekoparty's 2024 Main CTF. 

Find the writeup here: [https://blog.kulkan.com/our-nmap-ctf-challenge-for-ekoparty-cf55379bf000](https://blog.kulkan.com/our-nmap-ctf-challenge-for-ekoparty-cf55379bf000)

## Running the challenge:

Clone the repository and build the challenge:

```
git clone https://github.com/kulkansecurity/ctf-challenge-ekoparty-2024
cd ctf-challenge-ekoparty-2024
docker build -t kulkan-challenge-2024 .
```

Running

```
docker run --rm -it -p 5000:5000 ctf-challenge-ekoparty-2024
```

The challenge should now be accesible from http://localhost:5000
