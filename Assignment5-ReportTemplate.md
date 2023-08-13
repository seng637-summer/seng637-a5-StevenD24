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

### Reliability Demonstration Charts

1. Upon evaluation of the system's reliability metrics, the threshold for an acceptable Mean Time To Failure (MTTF) was delineated. We employed a trial-and-error method to iteratively adjust the Failure Input Output (FIO) to ascertain this. After multiple iterations, it was ascertained that the FIO aligned precisely at a ratio of 750/31, translating to approximately 24.194 failures per interval. Consequently, this results in an MTTF of 0.0413, establishing our operational reliability benchmark.

<img src="https://github.com/seng637-summer/seng637-a5-StevenD24/assets/105379503/fa651375-d652-457a-b185-00b953e49032" alt="RDC MTTFmin Normal" width="641" />
#
2. Upon further examination of the system's reliability metrics, we assessed a scenario with an MTTF value that's precisely half the previously established minimum. Through our evaluations, this translated to an MTTF of 0.0823. To derive this, the Failure Input Output (FIO) was adjusted and determined to be at a ratio of 375/31, which is approximately 12.096 failures per interval. Under these parameters, it was observed that the System Under Test (SUT) almost instantaneously transitioned into the reject region.   
     
<img width="641" alt="image" src="https://github.com/seng637-summer/seng637-a5-StevenD24/assets/105379503/6c186a99-120c-4b3c-a17b-008e6d3f350a">
#
3. Further into our systematic analysis of the system's reliability metrics, we investigated a scenario benchmarked at double the initial minimum MTTF. This exploration yielded an MTTF value of 0.0207. To achieve this, the Failure Input Output (FIO) was meticulously adjusted, settling at a ratio of 1500/31. This equates to approximately 48.387 failures per interval. Notably, with these parameters in play, the System Under Test (SUT) made a swift transition into the accepted region.
     
<img width="641" alt="image" src="https://github.com/seng637-summer/seng637-a5-StevenD24/assets/105379503/09a3f064-ea79-4309-844e-1796b6cb43f4">

### Advantages

1. **Explicit Risk Quantification**: RDC allows decision-makers to weigh the consequences of release decisions through explicit risk parameters like α (producer's risk threshold), β (customer's risk threshold), and γ (the discrimination ratio).

2. **Easy Decision Making**: It provides three different regions that reflect whether the system should be accepted, needs more testing, or should be rejected. This allows flexibility in decision-making and potentially helps in reaching a conclusion more quickly.

3. **Integration with Existing Tools**: RDC.xls is developed to work within Microsoft Excel, a commonly used tool in many organizations. It accepts the same failure data required for other reliability tools like CASRE, making integration and application easier.

4. **Open Source**: As an open-source tool, RDC allows for broader accessibility and can be modified to fit specific organizational needs.

### Disadvantages

1. **Complexity in Implementation**: The creation of RDC in Excel was noted to require considerable experimentation to achieve the desired graph. Some rewriting of the form of equations was also needed. Thus, using and adapting the tool might require some technical expertise and effort.

2. **Compatibility Issues**: The Excel macros and programming in the spreadsheets was dated and our group experienced compatibility issues with the spreadsheet with the newer versions of the Microsoft Excel on macOS. 

3. **Possibility of Incorrect Parameters**: The decision to accept or reject a system depends on the risk thresholds set by the producer. Incorrectly set parameters might lead to wrong decisions such as rejecting a satisfactory system or accepting an unsatisfactory one.

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
