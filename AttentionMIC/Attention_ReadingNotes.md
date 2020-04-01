# The basic method of trainning

python train_attention_multiruns.py

--num_epochs 10
--batch_size 128
--id decisionlevelsingleattention_128_3_0.6_lr0.0005_noannealing_res
--loss_type BCE
--lr 0.0005 
--dropout_rate 0.6 
--hidden_size 128 
--emb_layers 3 
--log_dir ./log/ISMIR2019/ 
--model_type attention

# About torch.optim.lr_scheduler.MultiStepLRV

The **MultiStepLRV** function is used to decrease the learning rate depends on the milestones from the input parameters during the epochs period. 

# Others

pip install --upgrade -i https://pypi.tuna.tsinghua.edu.cn/simple scikit-learn