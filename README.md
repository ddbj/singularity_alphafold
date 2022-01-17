# singularity_alphafold
Ubuntu 18.04にalphafold 2.1をインストールしたsingularity imageを作成するためのSingularity definition fileです。GPUを使用する場合はSingularity_GPU、GPUを使用しない場合はSingularity_CPUを使用してimageをビルドしてください。
## imageのビルド
```
$ sudo singularity build alphafold-2.1-xPU.sif Singularity_xPU
```
