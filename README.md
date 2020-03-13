# paper 1
## Confusionset-guided Pointer Networks for Chinese Spelling Check
* Confusionsets are a lexicon of commonly confused characters.换言之，就是常见的易混淆的字符的集合 
* The clear novelty of our work, however, is the infusion of Confusionsets with Pointer Networks, which help reduce the search space and vastly improve the probability of generating correct characters. 工作明显的创新之处在于将混淆集和指针网络结合，这有助于减少搜索空间并大大提高生成正确字符的概率。
* According to the statistic result of incorrect Chinese characters collected from the Internet (Liu et al., 2010),83% of these errors were related to phonological similarity, and 48% of them were related to visual similarity between the involved characters. 根据统计，在中文错字中，83%是与音相似相关，48%的错误是与形相似相关
### Discussion and Future Work
* 文章仅限于发现拼写的错误，并用正确的字去替换，限于三类错误（音，形，意思相近）
* 除了spelling error外，还有grammar error 对于此类的问题，尚未得到有效的解决，一种方法是要重新考虑如何将confusionset合并到编码器-解码器体系结构中。（One concern is that we need to reconsider how to incorporate Confusionsets into the encoder-decoder architecture.）
* 文章还有个局限就是输入输出的文本的长度是一样的

