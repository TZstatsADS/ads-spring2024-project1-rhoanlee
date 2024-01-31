# ADS Project 1: What made you happy today?
### Code lib Folder

The lib directory contains various files with function definitions (but only function definitions - no code that actually runs).

* inner_join(demo_data, by = "wid") %>%  :  join 2 datasets by wid(worker id)
* hm_data_10 <- hm_data[hm_data$gender=="f" & hm_data$age>=10 & hm_data$age<20,]  : define hm_data_10 as females of age between 10~20
* word_count_female <- bag_of_words_female %>%
  count(word, sort = TRUE)  : variable for counting words
* ggplot()  : creating graphic
* wordcloud()  : creating word cloud
