FROM python:3.11-slim

# Install minimal system dependencies (only what's truly needed)
RUN apt-get update && apt-get install -y --no-install-recommends \
    git \
    ca-certificates \
    && rm -rf /var/lib/apt/lists/*

# Create non-root user for security
RUN useradd -m -s /bin/bash codespace

# Set working directory
WORKDIR /workspace

# Allow codespace user to install pip packages
RUN chown -R codespace:codespace /workspace

USER codespace

# Pre-install pip dependencies for faster Codespace startup
COPY ../requirements.txt .
RUN pip install --no-cache-dir --user -r requirements.txt

CMD ["sleep", "infinity"]