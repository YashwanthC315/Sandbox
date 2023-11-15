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
7. Average views -> Give higher score if video has more views than average. Ex. channel avg views=10000, video views -> 10000=3, 20000=4, etc. (Parameters can be changed)

-----
## Calculation

Total score=Score of (Upload date + Views + Likes + Dislikes + Comments + Subscribers + Average Views) /7

-----
### Example Table

| Title | Link | Channel | Subscribers | Score | Upload Date | Score | Views | Score | Average Views | Score | Likes | Score | Dislikes | Score | Comments | Score | Total Score |
|:-----:|:----:|:-------:|:-----------:|:-----:|:-----------:|:-----:|:-----:|:-----:|:-------------:|:-----:|:-----:|:-----:|:--------:|:-----:|:--------:|:-----:|:-----------:|
|Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]|https://www.youtube.com/watch?v=X48VuDVv0do|TechWorld with Nana|948,000|2020-11-06|
|Kubernetes Crash Course for Absolute Beginners [NEW]|https://www.youtube.com/watch?v=s_o8dwzRlu4|TechWorld with Nana|948,000|2021-09-30|
|Kubernetes in 5 mins|https://www.youtube.com/watch?v=PH-2FfFD2PU|VMware Cloud Native Apps|2017-05-16|
|What is Kubernetes - Kubernetes explained in 15 mins|https://www.youtube.com/watch?v=VnvRFRk_51k|TechWorld with Nana|948,000|2019-12-20|
|Kubernetes Crash Course: Learn the Basics and Build a Microservice Application|https://www.youtube.com/watch?v=XuSQU5Grv1g|KodeKloud|2023-03-31|


