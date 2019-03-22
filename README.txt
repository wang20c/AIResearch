================
Data description
================

This corpus comprises images collected from Twitter during four natural disasters, namely Typhoon Ruby (2014), Nepal Earthquake (2015), Ecuador Earthquake (2016), and Hurricane Matthew (2016). In addition to Twitter images, it contains images collected from Google using queries such as "damage building", "damage bridge", and "damage road" to deal with labeled data scarcity problem.

Data format of most of the files is self-explanatory and is organized as follows:

Typhoon Ruby:
-------------
Images are stored under the "ruby_typhoon" folder, which contains a total of 833 images.
"ruby.{train|dev|test}" files list the set of images and their ground-truth damage labels (separated by a space) used for training (500), development (167) and test (166).

Nepal Earthquake:
-----------------
Images are stored under the "nepal_eq" folder, which contains a total of 19,104 images.
"nepal.{train|dev|test}" files list the set of images and their ground-truth damage labels (separated by a space) used for training (11,463), development (3,821) and test (3,820).

Ecuador Earthquake:
-------------------
Images are stored under the "ecuador_eq" folder, which contains a total of 2,280 images.
"ecuador.{train|dev|test}" files list the set of images and their ground-truth damage labels (separated by a space) used for training (1,368), development (456) and test (456).

Hurricane Matthew:
------------------
Images are stored under the "matthew_hurricane" folder, which contains a total of 596 images.
"matthew.{train|dev|test}" files list the set of images and their ground-truth damage labels (separated by a space) used for training (357), development (120) and test (119).

Google Images:
--------------
Images are stored under the "ggImage" folder, which contains a total of 3,007 images.
"gg.{train|dev|test}" files list the set of images and their ground-truth damage labels (separated by a space) used for training (1,804), development (602) and test (601).

"classes.txt" file contains the mapping between category indices and names, i.e., 
0 none
1 mild
2 severe


====================
Citation information
====================

If you use this data in your research, please cite the following paper:

Dat T. Nguyen, Ferda Ofli, Muhammad Imran, Prasenjit Mitra. Damage Assessment from Social Media Imagery Data During Disasters. In Proceedings of IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM). August 2017.

@INPROCEEDINGS{DTNguyen:ASONAM17, 
author={Dat T. Nguyen and Ferda Ofli and Muhammad Imran and Prasenjit Mitra}, 
booktitle={IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM)}, 
title={Damage Assessment from Social Media Imagery Data During Disasters}, 
year={2017}, 
pages={}, 
month={Aug},
}


============
Terms of Use
============

THE DATA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

By downloading or using any of the material available on this site, you automatically acknowledge to the following conditions:

By way of example and not as a limitation, when using these materials, you shall not do any of the following: 
- Defame, abuse, harass, stalk, threaten or otherwise violate the legal rights (such as rights of privacy and publicity) of others; 
- Publish, post, distribute or disseminate any defamatory, infringing, obscene, indecent or unlawful material or information;

You will be liable for any loss or damage in connection with this data 
IN NO EVENT SHALL QCRI OR QCRI’s AFFILIATES BE LIABLE TO THE REQUESTER OR TO THE USER OF THE DATA SUPPLIED FOR ANY SPECIAL, INCIDENTAL, PUNITIVE, INDIRECT, EXEMPLARY, OR CONSEQUENTIAL DAMAGES.THIS DATA IS PROVIDED ON AN “AS IS” BASIS AND YOUR USE OF IT IS AT YOUR SOLE RISK.YOU WILL INDEMNIFY QCRI OR QCRI's AFFILIATES FOR ANY LOSS OR DAMAGE THEY MAY SUFFER ARISING OF ANY BREACH BY YOU OF THIS AGREEMENT.

- You will use the data only for research on humanitarian computing.
- You will keep the contents of these dataset(s) confidential (you can always share the tweet-ids).
- The dataset(s) will be deleted by you upon our request at any time (you can always keep the tweet-ids).
- The dataset(s) will be deleted by you upon completion of the research (you can always keep the tweet-ids).
- You will cite the corresponding paper in derived publications.
