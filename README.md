IFP Deep Learning Paper Repo
============================
Repo to make keeping an up-to-date list of papers easier.

The format is supposed to look good in github, and be easy to `grep`.

### File format
#### Filename
`lastname_year_venue_{first word of publication title}.md`

#### File contents
```
# filename

link

bibtex citation

# Tags  
+ tag_number_1

# Description  
Description goes here
```
#### Example usage:
See [zeiler_2014_eccv_visualizing.md](zeiler_2014_eccv_visualizing.md)

### Common tags
+ convnet  
+ imagenet  
+ hinton  

### Grep examples
Find papers by Girshick:
`ls | grep girshick`
Find papers tagged with convnet, by Girshick:
`grep -rl '+ convnet' . | grep girshick`
Find papers tagged with convnet, in 2014:
`grep -rl '+ convnet' . | grep 2014`
Find papers tagged with convnet, in eccv:
`grep -rl '+ convnet' . | grep cvpr`
