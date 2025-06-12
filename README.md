# bv-download
given a BV number or bilibili url, download the video, host using gradio

1. Maintain login credentials, keep updating credential.json every hour
2. Monitor private message, if receiving "link BVxxxxxxxx", proceed
3. Download video in highest fidelity possible
4. Use gradio to generate a public link to the video
5. Reply the link to private message
