# BERTNER
Pytorch Bertner


python run_ner.py --data_dir=data/ --bert_model=bert-base-cased --task_name=ner --output_dir=out --max_seq_length=128 --do_train --num_train_epochs 5 --do_eval --warmup_proportion=0.4
