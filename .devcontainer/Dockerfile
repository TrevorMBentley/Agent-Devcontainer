FROM ://microsoft.com
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
RUN apt-get update && apt-get install -y --no-install-recommends curl git jq && apt-get clean && rm -rf /var/lib/apt/lists/*
WORKDIR /workspace
