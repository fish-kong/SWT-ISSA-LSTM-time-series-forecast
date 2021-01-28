# SWT-ISSA-LSTM-time-series-forecast
The long and short-term memory network LSTM has attracted attention in recent years for the short-term time series prediction problem. However, because this method is a deep learning method, it usually faces the influence of many hyperparameters. As we all know, the setting of deep learning hyperparameters is not There is no clear guideline, and most of them use empirical methods, such as learning rate 1e-3, 1e-4, etc. The number of iterations is set according to the change of loss curve, etc. This method is simple to try and find the effect is better A group of people, time-consuming and labor-intensive. To this end, this paper will use the improved sparrow search algorithm ISSA to optimize the parameters of LSTM, while using synchronous squeeze wavelet SWT to filter the original data to reduce noise, and use the data of the noise reduction meeting to model, and finally use the example verification to show that, The prediction effect of the SWT-ISSA-LSTM model is better. 长短时记忆网络LSTM在针对短时时间序列预测问题上近来年受到大家的关注，但由于该方法为深度学习方法，通常面临着众多超参数的影响，而众所周知，关于深度学习超参数的设置并没有一直明确的指导方针，大多采用经验方法，比如学习率1e-3,1e-4啥的，迭代次数根据loss曲线的变化等进行设置，这种方法说简单的就是无限尝试，找到效果比较好的一组，耗时耗力。为此，本文将采用改进的麻雀搜索算法ISSA对 LSTM进行参数优化 , 同时采用同步挤压小波SWT对原始数据进行滤波降噪，并采用降噪会的数据进行建模，最后用实例验证表明 ,SWT-ISSA-LSTM 模型的预测效果更佳。
代码采用maltab2020b编写，需要的加我qq2919218574，新鲜出炉，注意收费的，收费的，收费的啊。详情看我csdn博客：https://blog.csdn.net/qq_41043389/article/details/113308384
