# Integrate SAST Scans in Release Pipeline

![Screenshot 2024-02-28 at 13 24 28](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/6fe23c06-14ee-4176-b3d9-9ea34aacbf4f)

![Screenshot 2024-02-28 at 13 26 44](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/c59ee19b-cb0c-4c88-b7e4-bf5f69f84f1b)

![Screenshot 2024-02-28 at 13 27 19](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/1f9fa06e-4419-4547-a53a-bb893a2c3e75)

![Screenshot 2024-02-28 at 13 28 17](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/5c45b35b-3060-42cc-9b36-baaaafc952b9)

![Screenshot 2024-02-28 at 13 28 35](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/06031664-9a57-460c-b741-67c7f7b28aef)

we have a Nodejs app so we will use njsscan:

![Screenshot 2024-02-28 at 13 29 21](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/4a2aed70-a6ce-49fc-bdd3-3140545940c7)

![Screenshot 2024-02-28 at 13 29 43](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/bd23ac61-b9d2-4a99-9dc7-6f81152fa60f)

![Screenshot 2024-02-28 at 13 30 21](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/84aff2e4-5b7a-490c-ada3-23b9f73c4d1f)

we add njjsscan in our pipeline:

![Screenshot 2024-02-28 at 13 31 18](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/33f3a915-e35a-4f08-a52a-c5885e7c524c)

we have 1 finding from the scan:

![Screenshot 2024-02-28 at 13 33 43](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/c7017b7a-0f57-4510-99da-38c2da723937)

There are different levels od Security:

![Screenshot 2024-02-28 at 13 36 36](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/1ea37ff9-04b5-4b8c-81c4-7528014c9e25)


![Screenshot 2024-02-28 at 13 39 08](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/8bccea5f-0e50-40e1-95c0-17aab215da66)

we will another test: semgrep

![Screenshot 2024-02-28 at 13 39 55](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/79cf919f-5fc7-42e5-a3bb-dafe02b0c235)

![Screenshot 2024-02-28 at 13 40 26](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/2325c20c-f238-4f3b-8547-2ba07b5c45ad)

![Screenshot 2024-02-28 at 13 42 13](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/e78ce117-abf0-4e8a-a38f-f806a933720f)


semgrep found 23 findings!

![Screenshot 2024-02-28 at 13 42 47](https://github.com/redjules/Integrate-SAST-Scans-in-Release-Pipeline/assets/106017493/7b375d09-b339-4b19-9f88-a9e037344d28)


