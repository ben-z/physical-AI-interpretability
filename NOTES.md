### Example commands

#### ACT

Force per-frame attention:

```sh
export DATASET=observabot/so101_die_mat1 EPISODE=1 POLICY=observabot/act_so101_die_mat1_b128_020000 PYTHONPATH=. HF_LEROBOT_HOME=../lerobot/hf-home; python examples/visualise_original_data_attention.py --dataset-repo-id $DATASET --episode-id $EPISODE --policy-path $POLICY --output-dir ./output/attention_analysis_results/${DATASET}/${EPISODE}/${POLICY} --force-per-frame-attention
```