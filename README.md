# alphapose_docker
Dockerfile to run alphapose

`docker run --rm -it tchataing/alphapose`  
`$ python scripts/demo_inference.py --cfg configs/coco/resnet/256x192_res50_lr1e-3_1x.yaml --checkpoint pretrained_models/fast_res50_256x192.pth --indir examples/demo/ --gpus -1 --debug --pose_track --outdir test
`
