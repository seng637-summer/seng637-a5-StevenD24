**SENG 637- Dependability and Reliability of Software Systems***

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       |   |
|-----------------|---|
| Student Names:  |   |
|                 |   |
|                 |   |
|                 |   |

# Introduction

# 

# Assessment Using Reliability Growth Testing 

# Assessment Using Reliability Demonstration Chart 

<br>

Reliability Demonstration Charts
<br>
1. Upon evaluation of the system's reliability metrics, the threshold for an acceptable Mean Time To Failure (MTTF) was delineated. We employed a trial-and-error method to iteratively adjust the Failure Input Output (FIO) to ascertain this. After multiple iterations, it was ascertained that the FIO aligned precisely at a ratio of 750/31, translating to approximately 24.194 failures per interval. Consequently, this results in an MTTF of 0.0413, establishing our operational reliability benchmark.

<img src="https://github.com/seng637-summer/seng637-a5-StevenD24/assets/105379503/fa651375-d652-457a-b185-00b953e49032" alt="RDC MTTFmin Normal" width="641" />
       
2. Upon further examination of the system's reliability metrics, we assessed a scenario with an MTTF value that's precisely half the previously established minimum. Through our evaluations, this translated to an MTTF of 0.0823. To derive this, the Failure Input Output (FIO) was adjusted and determined to be at a ratio of 375/31, which is approximately 12.096 failures per interval. Under these parameters, it was observed that the System Under Test (SUT) almost instantaneously transitioned into the reject region.   
     
<img width="641" alt="image" src="https://github.com/seng637-summer/seng637-a5-StevenD24/assets/105379503/6c186a99-120c-4b3c-a17b-008e6d3f350a">
     
3. Further into our systematic analysis of the system's reliability metrics, we investigated a scenario benchmarked at double the initial minimum MTTF. This exploration yielded an MTTF value of 0.0207. To achieve this, the Failure Input Output (FIO) was meticulously adjusted, settling at a ratio of 1500/31. This equates to approximately 48.387 failures per interval. Notably, with these parameters in play, the System Under Test (SUT) made a swift transition into the accepted region.
     
<img width="641" alt="image" src="https://github.com/seng637-summer/seng637-a5-StevenD24/assets/105379503/09a3f064-ea79-4309-844e-1796b6cb43f4">

# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
