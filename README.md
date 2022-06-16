# 中文正反同义数据集 #NLP#消歧任务#正反同义格式

近年来,将神经网络模型应用于自然语言处理任务已经成为主流趋势，神经网络的可解释性问题也受到学界的广泛关注。
本文以现代汉语“差点（没）VP”格式为切入点，通过正反同义与否的判别任务对神经网络提取了哪些特征，学到了什么知识，为什么会表现得很好等问题作了详细的探究。
我们首先在前人研究的基础上，利用真实语料制作了“差点（没）VP”数据集，并在句子相似度计算、释义识别等任务中表现很好的RoBERTa模型上进行了训练。
然后，我们通过计算积分梯度和语言学知识归纳两种方式，找到了一些潜在的对模型判别有帮助的形式线索，并通过将形式线索剔除的方式进行了验证。
研究发现，对神经网络模型判别有帮助的形式线索很大一部分出现在“差点（没）VP”句子的核心区域，多是VP短语的核心动词或作补语的谓词，且基本都带有积极或消极的语义色彩。
模型学到的知识本质上就是形式线索在数据中的分布知识，模型判别准确率高的原因是因为模型捕捉形式线索的分布特征的能力是很强的。
当然，这些形式线索所携带的语义信息往往能够反映出人类的判别知识。从某种程度来说，如果不在训练数据中显性地加注语义知识，神经网络学到的知识与人类知识之间的关系更像是一种形式与意义的关系。

相关数据待开源，敬请期待，详情咨询邮箱1900014165@pku.edu.cn

