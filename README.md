# Here are some useful tricks

## Data trasfer
```
# trasferring large files to USB (remember to safely unmount)
cp -r some_local_file destination & progress -mp $!
# transfer to ssh server
rsync -avz some_file USER@server.xxx:DESTINATION
```

## slurm
```
ssh -X username@ssh.ccv.brown.edu
# load mamba conda
module load miniforge/23.11.0-0s
source /oscar/runtime/software/external/miniforge/23.11.0-0/etc/profile.d/conda.sh
# load cuda
module load cuda/12.2
```
