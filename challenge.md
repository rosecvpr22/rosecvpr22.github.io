---
layout: default
---

<div style="text-align: center">
<u><g8>Challenge</g8></u>
</div>

## Important dates
- Challenge announcement: <strong>Jan 10, 2022</strong>
- Release of testing data: <strong>Feb 10, 2022</strong>
- Leaderboard open: <strong>Feb 25, 2022</strong>
- Challenge submission deadline [paper track]: <strong>March 10, 2022</strong>
- Challenge submission deadline: <strong>May 31, 2022</strong>
- Winner announcement: <strong>June 05, 2022</strong>

## Challenge Overview
<div style="text-align: justify">
This challenge invites participants from both academia and industry to develop robust activity recognition models which will be tested for robustness against various perturbations. 
<br>
<br>
The robustness will be evaluated based on the model's performance on the test set with natural corruptions and perturbations. We will test the model robustness against natural perturbations including spatial corruptions (gaussian noise, shot noise, impulse noise, etc.), temporal corruptions (sampling rate, freezing, streaming issues, etc. ), camera related perturbations (rotation, translation, jittering, etc.), and compression perturbations (lossy video encodings).
<br>
<br>
We will use a public leaderboard for this challenge where the participants can submit their solutions which will be automatically evaluated.
</div>


## Challenge track
<div style="text-align: justify">
The challenge is focused on developing solutions that reduce the gap in performance between training set and real-world testing scenario. The goal of this challenge is to promote methods that can handle the various types of perturbations and corruptions observed in real-world data. 
<ul>
<li>Activity recognition track: This track will involve recognition of activities included in Kinetics, UCF-101 and HMDB dataset. The evaluation data will contain perturbed and corrupted samples based on above mentioned criteria, with the goal to test a model's robustness against various natural, camera-related and compression related perturbations and corruptions.</li>
</ul>
</div>

## Evaluation
<div style="text-align: justify">
We will use existing benchmark datasets in activity recognition for the evaluation including Kinetics, UCF-101, and HMDB. We will release a mini-set and a full-set comprised of modified data from all datasets which will include perturbations and corruptions. The mini-set can be used for self-evaluation while the full-set will be used for submission to be evaluated for the comptetition. The evaluation will be performed using the <b>accuracy metric</b> on the <b>full-set</b>.
<br>
<br>
More details on the evaluation process, test data and the evaluation server link will be up soon!
</div>


## Challenge paper submission guidelines
<div style="text-align: justify">
Participants willing to submit paper for consideration under the challenge track should follow the given guidelines. Failure to adhere to these guidelines will result in rejection of the paper, however the evaluation scores will still be considered for non-paper track.
<ul>
<li> The manuscript should follow CVPR 2022 paper template. The paper can have maximum of <b>8 pages</b> (excluding references) on above mentioned topics. We encourage the authors to submit 4 page papers. Please refer to <a href="https://cvpr2022.thecvf.com/sites/default/files/2021-10/cvpr2022-author_kit-v1_1-1.zip"><b>CVPR 2022 author kit</b></a> for detailed formatting instructions. </li>
<li> Submitted manuscript should follow the double-blind policy following CVPR 2022.</li>
<li> Dual submission to <b>CVPR 2022</b> and <b>ROSE 2022</b> is allowed, however the manuscript must contain substantial original contents that is not submitted to <b>any other</b> workshop, conference or journal.</li>
<li> Submissions will be desk-rejected without review if they:
    <ul>
    <li> violate the double-blind or dual-submission policy</li>
    <li> have more than 8 pages (excluding references)</li>
    </ul>
</li>
<li> Submitted manuscripts will be peer reviewed under the double-blind policy of CVPR 2022. Submission should be done online through the <b>CMT submission system</b>.</li>
<li> Accepted papers will be available at the workshop webpage. They will also be made available in the main conference proceedings if the authors agree (only for full-length papers not published at CVPR 2022).</li>
</ul>
</div>


## Tentative schedule
<div style="text-align: justify">
<ul>
<li> <b>Feb 10, 2022:</b> <u>Test data release</u> <br>We will release the mini-set for the challenge track. The full-set will also be released shortly. </li>
<li> <b>Feb 25, 2022:</b> <u>Leaderboard open</u> <br>The evaluation server and leaderboard will be open to public for challenge participation. </li>
<li> <b>March 10, 2022:</b> <u>Challenge submission deadline for paper track</u> <br>Challenge participants willing to submit a paper to the workshop should submit their final manuscript with scores by this date. The participants may continue to submit for non-paper track until May 31, 2022, but those evaluations will not be considered for the paper. </li>
<li> <b>April 01, 2022:</b> <u>Notification to authors</u> <br>Authors of submitted papers will be notified.</li>
<li> <b>April 08, 2022:</b> <u>Camera ready deadline</u> <br>Selected papers should submit a well-formatted camera ready paper by this deadline.</li>
<li> <b>May 31, 2022:</b> <u>Challenge submission deadline (non-paper track)</u> <br>Participants for the non-paper track can submit final evaluation files by this date for challenge consideration. </li>
<li> <b>June 05, 2022:</b> <u>Challenge winner announcement</u> <br>Highest ranking participants will be asked to send the solutions and reports to the organizers.</li>
<li> <b>June 20, 2022:</b> <u>Workshop</u> <br>Winners will presentation their solution. Presentation duration will be announced later.</li>
</ul>
</div>

### Join our **[mailing list](https://groups.google.com/g/robustness-challenge)** for updates.
For any questions, please contact **Yogesh Rawat [yogesh@crcv.ucf.edu]** and <br>**Vibhav Vineet [Vibhav.Vineet@microsoft.com]**.
