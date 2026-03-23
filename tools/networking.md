# Networking Tools

## Core Capabilities

- Protocols: HTTP, TCP, UDP, DNS, TLS
- API design: REST, GraphQL, gRPC
- Security: TLS, authentication, authorization
- Troubleshooting: connectivity, latency, DNS issues

## Local vs Remote

- Distinguish local vs cloud execution
- Adapt commands accordingly
- Avoid local-only assumptions

## Debugging

```bash
# Connectivity
curl -v              # Verbose request
curl -I              # Headers only
wget                 # Download

# DNS
dig domain           # DNS lookup
nslookup domain      # Name lookup
host domain          # DNS lookup

# Ports
telnet host port     # Test connection
nc -zv host port     # Check port
ss -tuln             # Listening ports
```

## Proxy

```bash
# Environment
export HTTP_PROXY=http://proxy:port
export HTTPS_PROXY=http://proxy:port
export NO_PROXY=localhost,127.0.0.1

# curl
curl --proxy http://proxy:port ...

# wget
wget --proxy=on ...
```

## Certificates

```bash
# Check cert
openssl s_client -connect host:port

# View cert
openssl x509 -in file.crt -text
```

## HTTP Debugging

```bash
# Headers
curl -i              # Include headers
curl -H "Header: val" # Custom header

# Methods
curl -X GET/POST/PUT/DELETE

# Body
curl -d '{"key": "val"}'
curl -F file=@file
```

## Failure Handling

- Detect connection failures early
- Handle rate limits
- Implement retry logic
- Provide fallback solutions
