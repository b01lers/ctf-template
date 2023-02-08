Checklist For PRs:

- [ ] Is solvable (you don't have to solve it blind, just go through the solve and validate it and sanity check it)
- [ ] `flag.txt` is present  in `./solve` and contains just the flag.
- [ ] Flag is in `flag{...}` format (if impossible, the format is noted in the description.)
- [ ] Writeup is present in `solve.md` under `./solve`
- [ ] Writeup is high quality and completely explains how to solve the challenge from scratch
- [ ] `chal.json` is present in the challenge root directory and contains:
  - [ ] Challenge Title
  - [ ] Challenge Author
  - [ ] Challenge Difficulty `[Easy, Medium, Hard]`
  - [ ] Challenge Description (for distribution, this is your flavor text)
- [ ] Local build files are present in `./src` if applicable (Makefile etc)
- [ ] Remote deployment files are present in `./deploy` if applicable.
  - [ ] xinetd.conf (if using xinetd)
  - [ ] Dockerfile
  - [ ] Dockerfile-build (if applicable)
  - [ ] docker-compose.yml
  - [ ] wrapper.sh


