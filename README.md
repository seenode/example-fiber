# Deploy Fiber on Seenode in Seconds

This is a minimal and production-ready Fiber application set up for deployment on [Seenode](https://seenode.com).

### Deploy in Minutes
Check our [Fiber deployment guide](https://seenode.com/docs/frameworks/go/fiber/) for details.

## How to Deploy on Seenode

1. **Connect Your Repository**: Open the [Seenode dashboard](https://cloud.seenode.com), select **New Web Service**, and connect this repository.
2. **Confirm Settings**:
    - **Build Command**: `go build -o app main.go`
    - **Start Command**: `./app`
3. **Deploy**: Click **Create Web Service**.

Your Fiber app will go live at a public URL.

### Key Notes

- **Port Binding**: This app listens on port `80`. Make sure your Fiber code explicitly uses `app.Listen(":80")`.
- **Minimal Build**: A single binary makes it simple to deploy and maintain.
- **Horizontal Scaling**: Easily scale your service when traffic spikes.
