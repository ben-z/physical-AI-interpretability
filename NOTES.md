Example command:

```sh
export DATASET=observabot/so101_die_mat1 POLICY=observabot/act_so101_die_mat1_b128_005000 PYTHONPATH=. HF_LEROBOT_HOME=../lerobot/hf-home; python examples/visualise_original_data_attention.py --dataset-repo-id $DATASET --episode-id 0 --policy-path $POLICY --output-dir ./output/attention_analysis_results/${DATASET}/${POLICY}
```