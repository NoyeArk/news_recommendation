# 中间结果

## 召回

| 文件名 | 说明 |
| ----- | ---- |
| itemcf_i2i_sim.pkl | 基于 ItemCF 的物品相似度 |
| emb_i2i_sim.pkl | 基于 Embedding 的物品相似度 |
| user_youtube_emb.pkl | YoutubeDNN 训练得到的用户 Embedding |
| item_youtube_emb.pkl | YoutubeDNN 训练得到的物品 Embedding |
| youtube_u2i_dict.pkl | YoutubeDNN 召回结果 |
| itemcf_recall_dict.pkl | 基于物品相似度的 ItemCF 召回结果 |
| embedding_sim_item_recall.pkl | 基于 Embedding 的 ItemCF 召回结果 |
| youtubednn_usercf_recall.pkl | 基于 YoutubeDNN 得到的用户 Embedding 的UserCF 召回结果 |
| cold_start_items_raw_dict.pkl | 冷启动召回的还未筛选的文章 |
| cold_start_user_items_dict.pkl | 冷启动召回结果 |
| final_recall_items_dict.pkl | 不同召回通道合并的结果 |

## 特征工程

| 文件名 | 说明 |
| ----- | ---- |
| item_w2v_emb.pkl | Word2Vec 训练得到的物品嵌入字典 |
| user_info.csv | 构造得到的用户特征 |
| trn_user_item_feats_df.csv | 训练集用户的所有特征 |

## 排序模型
| 文件名 | 说明 |
| ----- | ---- |
| lgb_ranker_score.csv | lgb_ranker 排序模型预测的分数 |