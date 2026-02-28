
# Simple Architecture Diagram Tool for AWS

Template-based, shareable AWS architecture diagram tool (share via image or URL).

## Demo

https://aim2bpg.github.io/easy-diagram-for-aws/

## Included Resources

| Category | Resources |
|---|---|
| System Management | Session Manager |
| Data Store | Aurora, DynamoDB, EFS, ElastiCache, RDS |
| Networking | ACM, ALB, ELB, API Gateway, CloudFront, NAT Gateway, Network Firewall, VPC Internal, WAF |
| Computing | FE layer + ALB (internal), EC2 ⇄ Fargate, Lambda ⇄ VPC Lambda |
| CI/CD | CodePipeline, ECR, ECS, GitHub ⇄ GitLab |

## Usage

1. Open `index.html` in your browser (or visit the Demo URL above).
2. Click resource buttons in the sidebar to toggle visibility.
3. Use the **Share URL** button to copy a link representing the current diagram.
4. Use the **Copy Diagram** button to copy a PNG image of the diagram to your clipboard.

## License

MIT
