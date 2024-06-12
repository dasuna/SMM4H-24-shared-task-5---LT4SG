# Project Overview

Many children are diagnosed with disorders that can impact their daily life and can last throughout their lifetime. For example, in the United States, 17% of children are diagnosed with a developmental disability, and 8% of children are diagnosed with asthma. Meanwhile, sources of data for assessing the association of these outcomes with pregnancy exposures remain limited.

This binary classification task involves automatically distinguishing tweets, posted by users who had reported their pregnancy on Twitter, that report having a child with attention-deficit/hyperactivity disorder (ADHD), autism spectrum disorders (ASD), delayed speech, or asthma (annotated as "1"), from tweets that merely mention a disorder (annotated as "0"). Sample tweets are shown in the table below.

This task enables the use of Twitter on a large scale not only for epidemiologic studies but, more generally, to explore parents' experiences and directly target support interventions. The training, validation, and test sets contain 7398 tweets, 389 tweets, and 1947 tweets, respectively. A benchmark classifier, based on a RoBERTa-Large pretrained model, achieved an F1-score of 0.93 for the "positive" class (i.e., tweets that report having a child with a disorder).

## Sample Tweets

| Tweet ID          | Text                                                                                                                                                                           | Label |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| 1210574839632793600 | Finally a dr has diagnosed my 3.5yr old with asthma. Now he will be on chronic medicine and we can hopefully keep him healthy and thriving.                                     | 1     |
| 1418466938389352451 | Can u give any tips to "live with it" please. I think my son has ADD. Trying to help him                                                                                      | 0     |
| 1357889939283795969 | Flying tomorrow...during a pandemic with a nonverbal 3 year old. We could use some prayers, please.😝🥴                                                                         | 1     |
| 1473729432946884627 | So Maxine Waters can be maskless on a plane but I can't fly with my 2 year old cause she won't wear a mask? Kids with autism are being banned from flying because they won't wear a mask? | 0     |
