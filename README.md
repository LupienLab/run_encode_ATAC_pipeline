# run_encode_ATAC_pipeline


Run ENCODE ATAC pipeline on Mordor:

## STEP1: Copy example json to own directory
cp /mnt/work1/users/lupiengroup/pipelines/encode-atac-pipeline-v1.9.0/example.json /path/to/directory


## STEP2: Edit example json according to your own sample

## STEP3: Run following command with edited json file
bash /mnt/work1/users/lupiengroup/pipelines/encode-atac-pipeline-v1.9.0/run_encode-atac-pipeline.sh edited.example.json
 

## Important things to note:
How to edit JSON:
1. https://github.com/ENCODE-DCC/atac-seq-pipeline/blob/master/docs/input_short.md
2. https://github.com/ENCODE-DCC/atac-seq-pipeline/blob/master/docs/input.md

## Pipeline protocol:
https://www.encodeproject.org/atac-seq/
https://docs.google.com/document/d/1f0Cm4vRyDQDu0bMehHD7P7KOMxTOP-HiNoIvL1VcBt8/edit

## Organize output:

![croo](https://github.com/LupienLab/run_encode_ATAC_pipeline/blob/main/croo.png)

## Organize QC:
![qc](https://github.com/LupienLab/run_encode_ATAC_pipeline/blob/main/qc.png)
