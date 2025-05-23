# Dev Setup

Clone the repository and install dependencies to a virtual environment:

```console
# Mac
docker run --rm -p 7880:7880 -p 7881:7881 -p 7882:7882/udp livekit/livekit-server --dev --node-ip=127.0.0.1
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 agent.py download-files
python3 agent.py console
```
