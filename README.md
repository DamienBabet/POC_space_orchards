# Space orchards: tracking orchards from satellite imagery

Our experience in the NTTS 2025 big data hackathon confirmed that segformer model could train efficiently on Sentinel2 data and CLC+ labels.

We want to test a new use case: tracking changes in orchards for French agricultural statistics.

Most crops in France are well known thanks to Common Agricultural Policy (CAP) databases, where farmers declare each field and each crop. But for some crops, and orchards are among them, the coverage is lower (typically about 70%). As a consequence, we might miss some farms when we plan a survey about orchards.

We expect orchards to be easier to classify from satellite data than other crops, and we can use orchards that are declared in CAP publicly available databases as training data.

The goal of this POC is to test :
- the use of the SSPCloud with Onyxia platform do train models on satellite data
- the recycling to the hackathon stack
- the performance of segformer models for tracking orchards.
