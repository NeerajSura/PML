LightGBM:
params = {
            'objective': 'binary',
            'boosting_type': 'gbdt',
#             'boosting_type': 'rf',
            'nthread': 4,
            'learning_rate': 0.02,  # 02,
            'num_leaves': 15,
            'feature_fraction': 0.9,
            'bagging_fraction': 0.7,
            'bagging_freq': 1,
            'early_stopping_round':5,
            'max_depth':2,
            'reg_alpha': 0.041545473,
            'reg_lambda': 0.0735294,
            'min_split_gain': 0.0222415,
            'min_child_weight': 60,
            'seed': 0,
            'verbose': -1,
            'metric': 'auc',
}


Num_samples - 20K
Features - RA	JC	AA	PA	PPS	SPS
