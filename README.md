### Vagrant Ansible dssat csm

#### ! WORK IN PROGRESS

`vagrant up`

### To force provision:
`vagrant up --provision-with shell`

### Add reposiories


```bash
cd ..
git clone https://github.com/moisbo/cmake_fortran_template
git clone https://github.com/moisbo/dssat-csm
```

### To run provision ansible template
`vagrant up --provision-with ansible-template`

### To run provision ansible dssat
`vagrant up --provision-with ansible-dssat`
