# YouTube Video Rating

Rating the video from 1-5
-----

## Parameters

1. Upload date -> Give higher score to newer videos. Ex. 2023-5, 2022-4, etc. (Parameters can be changed)
2. Views -> Give higher score to more views recorded. Ex. 0-50000=1, 50001-100000=2, etc. (Parameters can be changed)
3. Likes -> Give higher score to more like ratio. Ex. views=2000, likes-> <50=1, 50-100=2, etc. (Parameters can be changed)
4. Dislikes -> Give higher score to less dislike ratio. Ex. views=2000, dislikes-> <50=5, 50-100=4, etc. (Parameters can be changed)
5. Comments -> Give higher score to more comment ratio. Ex. views=2000, comments-> <50=1, 50-100=2, etc. (Parameters can be changed)
6. Subscribers -> Give higher score to more subscribers. Ex. subscribers-> <5000=1, 5000-10000=2, etc. (Parameters can be changed)

-----
## Calculation

Total score=Score of (Upload date + Views + Likes + Dislikes + Comments + Subscribers) /6

-----
## Example Table

| Title | Link | Channel | Subscribers | Score | Upload Date | Score | Views | Score | Likes | Score | Dislikes | Score | Comments | Score | Total Score |
|:-----:|:----:|:-------:|:-----------:|:-----:|:-----------:|:-----:|:-----:|:-----:|:-----:|:-----:|:--------:|:-----:|:--------:|:-----:|:-----------:|
|Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]|https://www.youtube.com/watch?v=X48VuDVv0do|TechWorld with Nana|948,000|5|2020-11-06|3|7,000,317|4|96,767|3|921|4|4,041|5|4|
|Kubernetes Crash Course for Absolute Beginners [NEW]|https://www.youtube.com/watch?v=s_o8dwzRlu4|TechWorld with Nana|948,000|5|2021-09-30|4|2,169,585|2|40,020|2|472|3|1,342|3|3.16|
|Kubernetes in 5 mins|https://www.youtube.com/watch?v=PH-2FfFD2PU|VMware Cloud Native Apps|52,900|1|2017-05-16|1|2,224,968|2|27,098|1|1,984|1|13|1|1.16|
|What is Kubernetes - Kubernetes explained in 15 mins|https://www.youtube.com/watch?v=VnvRFRk_51k|TechWorld with Nana|948,000|5|2019-12-20|2|1,160,407|1|26,182|2|369|3|664|2|2.5|
|Kubernetes Crash Course: Learn the Basics and Build a Microservice Application|https://www.youtube.com/watch?v=XuSQU5Grv1g|KodeKloud|169,000|2|2023-03-31|5|858,632|1|4,935|5|84|5|154|2|3.33|


