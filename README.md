# SexTok  
  
**Title :** It’s not Sexually Suggestive; It’s Educative | Separating Sex Education from Suggestive Content on TikTok videos

Enfa George, Mihai Surdeanu, ACL Findings 2023 [[bib]](#citation)


[Computational Language Understanding Lab](https://clulab.org/), 
University Of Arizona

## Paper   
  
[Findings of the Association for Computational Linguistics: ACL 2023](https://aclanthology.org/2023.findings-acl.365/)

## Motivation

The current state of adolescent sex education in the United States is often criticized for being fragmented and inadequate, susceptible to political influence, and lacking comprehensive information. Only a small number of states require contraception education, and even fewer cover important topics like gender diversity and consent. This limited focus hampers the effectiveness of sex education programs, as highlighted by the American Academy of Pediatrics. 

<img src= "https://www.truthdig.com/wp-content/uploads/2017/06/sexed_500.jpg" width="40%"><img src="https://image.cagle.com/107727/750/107727.png" width="40%">

<sup align="centre"> Credit: Left - [Truthdig](https://www.truthdig.com/cartoons/abstinence-only-sex-ed) Right - [Cagle](https://www.cagle.com/pat-bagley/2012/03/sex-education)</sup>
</div>


Meanwhile, TikTok, a widely popular app among adolescents and youth, provides a platform for virtual sex education in a convenient, private, and inclusive space for sexual health information. However, these videos often face removal and shadow banning due to inaccuracies in community guidelines enforcement and mass reporting. Creators, especially those from marginalized communities, are disproportionately targeted by mass reporting. 

<img src = "https://helios-i.mashable.com/imagery/articles/02Fvbn4j2IGVdt4DU8Wy0gX/images-399.fit_lim.size_376x.jpg" height=300 align="centre"><img src=https://helios-i.mashable.com/imagery/articles/02Fvbn4j2IGVdt4DU8Wy0gX/images-401.fit_lim.size_376x.jpg height=300 align="centre">

<sup> Credit : [Mashable - Why is TikTok removing sex ed videos?](https://mashable.com/article/tiktok-sex-education-content-removal) </sup>

The project's goal is to develop a better system for distinguishing between sexual content and sex education, creating a dataset and establishing a baseline for future research.
  
## Citation  
 ```
@inproceedings{george-surdeanu-2023-sexually,  
    title = "It{'}s not Sexually Suggestive; It{'}s Educative | Separating Sex Education from Suggestive Content on {T}ik{T}ok videos",  
    author = "George, Enfa  and  
      Surdeanu, Mihai",  
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2023",  
    month = jul,  
    year = "2023",  
    address = "Toronto, Canada",  
    publisher = "Association for Computational Linguistics",  
    url = "https://aclanthology.org/2023.findings-acl.365",  
    pages = "5904--5915",  
    abstract = "We introduce SexTok, a multi-modal dataset composed of TikTok videos labeled as sexually suggestive (from the annotator{'}s point of view), sex-educational content, or neither. Such a dataset is necessary to address the challenge of distinguishing between sexually suggestive content and virtual sex education videos on TikTok. Children{'}s exposure to sexually suggestive videos has been shown to have adversarial effects on their development (Collins et al. 2017). Meanwhile, virtual sex education, especially on subjects that are more relevant to the LGBTQIA+ community, is very valuable (Mitchell et al. 2014). The platform{'}s current system removes/punishes some of both types of videos, even though they serve different purposes. Our dataset contains video URLs, and it is also audio transcribed. To validate its importance, we explore two transformer-based models for classifying the videos. Our preliminary results suggest that the task of distinguishing between these types of videos is learnable but challenging. These experiments suggest that this dataset is meaningful and invites further study on the subject.",  
}  
 ```

Dataset and Codebase with Experiment results to be shared soon.
