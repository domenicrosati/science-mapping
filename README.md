## OpenAlex Science Mapping Project

This repo contains the code for compiling the OpenAlex Science Map produced by QSS.

Directory Structure:
 * Data (gitignored directory for data inputs and outputs)
 * Experiments (ephemeral code for demonstrations and experiments)


### Using Compute Canada

If you have access to compute canada you can access the cluster with your username i.e.

```
username@niagara.computecanada.ca
```

You can submit jobs using the following shell script template:

```sh
#!/bin/bash
#SBATCH --time=00:15:00
#SBATCH --account=def-someuser
echo 'Hello, world!'
sleep 30
```

with the command:
```sh
$ sbatch job.sh
```


You can check on your jobs with `sq` or `squeue`.
