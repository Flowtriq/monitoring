# Flowtriq Agent

## From the [Flowtriq](https://flowtriq.com) website

Real-time network traffic monitoring and DDoS detection agent. Monitors inbound and outbound traffic, detects volumetric attacks, and reports to your Flowtriq dashboard for alerting and incident management.

## Requirements

You need a Flowtriq account to use this egg. Sign up at [flowtriq.com](https://flowtriq.com) and create a node in your dashboard to get an API key and Node UUID.

## Minimum Resources

| Resource | Minimum   |
|----------|-----------|
| CPU      | 1 core    |
| RAM      | 256 MB    |
| Disk     | 500 MB    |

## Server Ports

The agent does not require any exposed ports. It connects outbound to the Flowtriq API over HTTPS.

## Variables

| Variable          | Description                                                         | Required |
|-------------------|---------------------------------------------------------------------|----------|
| API Key           | Your Flowtriq API key from the dashboard                            | Yes      |
| Node UUID         | The UUID for this node, created in your Flowtriq dashboard          | Yes      |
| API Base URL      | API endpoint (only change for self-hosted instances)                | Yes      |
