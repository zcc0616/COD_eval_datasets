# COD_eval_datasets
伪装目标检测评价指标代码及数据集下载链接

1.评价指标
  
  Matlab代码
    
    修改Matlab/main.m中"--CamMapPath","--Models","--DataPath","--Datasets","--ResDir"所对应的参数，然后用Matlab运行"main.m"
  
  Python代码
    
    安装所需的os,torch,prettytable,argparse,cv2,tqdm包
    
    修改Python/Myeval.py中"--gt_root","--pred_root","--gpu_id","--data_lst","--model_lst"所对应参数，然后运行"Myeval.py"

2.数据集下载链接
  
  COD10K：链接：https://pan.baidu.com/s/16iDk9U0-LMZ5ocRomFipHA   提取码：tg19
  
  NC4K：链接：https://pan.baidu.com/s/1YCjh14eqal7DNnKGSo_3OQ   提取码：a0dq
  
  CAM-FR：链接：https://pan.baidu.com/s/1Cooq_sEzhiU6B6Zizqrh2w   提取码：do4l
  
  CPD（Camouflaged People Detection）：链接：https://pan.baidu.com/s/1COmdxF9VwR57yXPwB0C8Ww   提取码：x106
  
  MoCA-Mask（VCOD）：链接：https://pan.baidu.com/s/1moTkIR2n0HP9dIGD0wo5VA   提取码：yiqz
