

```bash
运行命令⬇️
python main_sft.py  --model_name_or_path "../transformers-code/03-PEFT/21-lora/bloom-1b4-zh"  --dataset_name "medalpaca/medical_meadow_medical_flashcards"  --local_data_dir "alpaca-gpt4" --dataset_sample 20000  --fed_alg "fedavg"  --num_clients 20  --sample_clients 2  --max_steps 10  --num_rounds 200 --batch_size 16 --gradient_accumulation_steps 1 --seq_length 512 --peft_lora_r 32 --peft_lora_alpha 64 --use_peft  --load_in_8bit  --output_dir "./output"  --template "alpaca"
