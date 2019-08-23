![AWS CodeBuild Builde Badge](https://codebuild.us-east-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiRm1MTnQ5Y1ErOUt4dlBPeE40cFN4UklITFJDbzM2QWVwTHc3bzdUa05VaDIzU1c5dnJSUVRxR2dTM08xZGZwRWROL09JL3BydVdBU3ZScmdzWE50dlpnPSIsIml2UGFyYW1ldGVyU3BlYyI6ImNDdTNyQ2hXU2VJQ0JiR24iLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=master)

# NHLP3
Serverless **N**HL **P**lay-by-**P**lay **P**rocessor *(hence NHLP3)* built using [AWS Lambda](https://aws.amazon.com/) and NHL's public APIs *(more information can be found at [Drew Hynes's](https://gitlab.com/dword4) [NHL Stats API Documentation project](https://gitlab.com/dword4/nhlapi/blob/master/stats-api.md))*.

![NHLP3 Diagram](https://pbs.twimg.com/media/ECWDcoCUEAAUnoC?format=png)

# PlayByPlayProcessor Function
The purpose of this function is to subscribe to the NHL play-by-play SNS messages published from the [NHLP3-EventPublisher](https://github.com/iansteph/NHLP3-EventPublisher).
