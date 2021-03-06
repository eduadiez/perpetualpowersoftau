Hash of the [`challenge`](https://ppot.blob.core.windows.net/public/challenge_0009) file for verification:

```
        af1d28b6 e1c2e68f 5c871f3e 01856f25
        2ef4f745 a3e39e3d 2aa3bc40 7f82b4a5
        feb2ba4c 303f90fb 15c86929 0611b732
        be31f29a 15e5d609 6f555cd0 683e5421
```

`response` was based on the hash:

```
        af1d28b6 e1c2e68f 5c871f3e 01856f25
        2ef4f745 a3e39e3d 2aa3bc40 7f82b4a5
        feb2ba4c 303f90fb 15c86929 0611b732
        be31f29a 15e5d609 6f555cd0 683e5421
```

Hash of the [`response`](https://ppot.blob.core.windows.net/public/response_0009_brecht) file for verification:

```
        2f21e33e d267b2c5 31fbafb1 89beb370
        a30166bf f9d97c02 42b7f3fc c650022c
        61868f0e b2000578 d852fb4a 71ceb9e9
        49337de4 9ec3ac48 1f2092db aac7a1de
```

Blake2b hash of the `new_challenge` file for participant #10:

```
        7fde382d 1bc12ae7 d3d99879 648e416b
        0540f39d 5e8f4945 229a7faa e97c3630
        9d54bf8b b8a0813c 67f89d19 9b2111b9
        0adb93c2 6b80fdd4 e3fe3640 860b7731
```

The above `new_challenge` file: https://ppot.blob.core.windows.net/public/challenge_0010

Brecht's attestation (from `brecht_attestation.txt`):

```
Hi,

Here's my attestation for round #9:

Date: 19-20 October 2019

Name: Brecht Devos (Loopring)

Location: Ghent, Belgium

Device(s): Dell XPS - 4 core i7 1.8GHz - 16GB RAM - Ubuntu 18.04 LTS

Challenge hash:
        af1d28b6 e1c2e68f 5c871f3e 01856f25
        2ef4f745 a3e39e3d 2aa3bc40 7f82b4a5
        feb2ba4c 303f90fb 15c86929 0611b732
        be31f29a 15e5d609 6f555cd0 683e5421 
        
Challenge file claims that it was based on the original contribution with a hash:
        cf0abf2f 06b4f5d1 3ab6ff1b 59e1ff40
        a9a2e9b4 fdf27eac 0b1345e8 c89cbc3f
        142d00d9 742d8e1a cc996425 cc626531
        fb1be7b2 86640d09 c2909072 f26b9a3e 
        
Response BLAKE2b hash:
        2f21e33e d267b2c5 31fbafb1 89beb370
        a30166bf f9d97c02 42b7f3fc c650022c
        61868f0e b2000578 d852fb4a 71ceb9e9
        49337de4 9ec3ac48 1f2092db aac7a1de 

URL: https://ppoteu.blob.core.windows.net/public/challenge_0009

Software used to generate the response: https://github.com/kobigurk/phase2-bn254/commit/bf852c168676a7afc5dd17b47ff9b8f394aeab8a

Entropy source: Key mashing, bitcoin hashes

Time taken: ~18 hours (computation) + ~12 hours (downloading/uploading)

Side channel defenses: None

Postprocessing:

- I copied the Blake2b hash from the CLI output of compute_constrained
- I uploaded the response via massive.io
- I rebooted the laptop
```
