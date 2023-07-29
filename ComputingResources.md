#Computing Resources

## ilab

CS Department [Instructional Lab Machines](https://report.cs.rutgers.edu/nagiosnotes/iLab-machines.html)

[Introduction to CS Resources](https://resources.cs.rutgers.edu/docs/new-users/introduction/)

[SLURM for GPU Tasks](https://resources.cs.rutgers.edu/docs/scheduler-for-gpu-jobs/)

[Important Notes, Resources Limiations](https://resources.cs.rutgers.edu/docs/limitation-enforced-on-cs-linux-machines/)

Features:

- 1TB Memory
- Support SLURM job scheduler
- Python Environment [Guideline](https://resources.cs.rutgers.edu/docs/using-python-on-cs-linux-machines/)
- GPU Specs:8 x RTX A4000
- CPU:2 x Dual Intel® Xeon Gold 6148 @ 2.40GHz, 80 vCores

## DBGroup

[cs-userid]@dbgroup.cs.rutgers.edu

Lab storage SSDs are mounted on dbgroup. (`/local/data` and `/local/data1`)

Features:
- 62GB Memory
- Intel(R) Xeon(R) Gold 6212U 2.40GHz - 12 cores, 24 vCores

## Amarel

Maintained by Rutgers Offices of Advanced Research Computing (OARC)

[Introduction](https://oarc.rutgers.edu/resources/amarel/)

**Important!** [Document](https://sites.google.com/view/cluster-user-guide)

Features:

- Need SLURM job scheduler
- More than 300 computing nodes
- Latest updated compute node:
  - 2x Intel Xeon Platinum 8358 (Ice Lake) Processors (48MB cache, 2.60GHz), 32-core processors, 64 vCores
  - 256GB Memory: 16x16GB DIMMS
- Need around two-day maintenance every month
- Contain different computing notes, need to specify nodelist if you want a stable runtime.

## Other Notes

- Amarel and dbgroup can be accessed by ssh through ilab when outside of the campus
- Sometimes Amarel is not stable
- Don't forget to check the storage limitation and requirement 

