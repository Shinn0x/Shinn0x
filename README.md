<!-- HEADER: follows GitHub's light / dark theme -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=rect&color=161b22&height=140&text=Naing%20Shin%20Thant%20Zaw&fontSize=40&fontColor=f0f6fc&fontAlignY=42&desc=Junior%20Cloud%20%2F%20DevOps%20Engineer%20%C2%B7%20AWS%20Certified%20%C2%B7%20Singapore&descSize=15&descAlignY=70">
    <img alt="Naing Shin Thant Zaw — Junior Cloud / DevOps Engineer, AWS Certified, Singapore" src="https://capsule-render.vercel.app/api?type=rect&color=f6f8fa&height=140&text=Naing%20Shin%20Thant%20Zaw&fontSize=40&fontColor=1f2328&fontAlignY=42&desc=Junior%20Cloud%20%2F%20DevOps%20Engineer%20%C2%B7%20AWS%20Certified%20%C2%B7%20Singapore&descSize=15&descAlignY=70" width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://localhostshinn.xyz"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-localhostshinn.xyz-57606a?style=flat-square&labelColor=24292f"></a>
  <a href="https://www.linkedin.com/in/naing-shin-thant-zaw/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-naing--shin--thant--zaw-57606a?style=flat-square&labelColor=24292f"></a>
  <a href="mailto:naingshinthantzaw04@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-naingshinthantzaw04%40gmail.com-57606a?style=flat-square&labelColor=24292f"></a>
  <img alt="Open to junior Cloud and DevOps opportunities" src="https://img.shields.io/badge/Status-open_to_work-57606a?style=flat-square&labelColor=24292f">
</p>

<br>

```text
role        Junior Cloud / DevOps Engineer
based       Singapore
education   Diploma in Information Technology, Singapore Polytechnic
internship  Tuas Power Generation — 3 production systems in 11 months
focus       AWS infrastructure, automation, troubleshooting
approach    build it, codify it, automate it, document it
```

<br>

<!-- CERTIFICATIONS -->
<h3 align="center">Certifications</h3>

<p align="center">
  <b>AWS Certified Solutions Architect – Associate</b><br>
  Amazon Web Services · Issued September 2026<br>
  <sub>Secure, scalable, resilient and cost-effective AWS architecture.</sub><br><br>
  <a href="https://www.credly.com/badges/6e871609-0c99-4973-b61a-cd750183e8a6"><img alt="Verify AWS Solutions Architect Associate certification on Credly" src="https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?style=flat-square&labelColor=24292f"></a>
</p>

<p align="center">
  <b>Google IT Automation with Python Professional Certificate</b><br>
  Google<br>
  <sub>Python automation, Git, Linux troubleshooting, configuration management and cloud administration.</sub><br><br>
  <a href="https://www.credly.com/badges/b2e80abf-1a06-4397-94cc-128459f81465/linked_in?t=tojy1y"><img alt="Verify Google IT Automation with Python Professional Certificate on Credly" src="https://img.shields.io/badge/Google-IT_Automation_with_Python-4285F4?style=flat-square&labelColor=24292f"></a>
</p>

<br>

<!-- STACK -->
<h3 align="center">Stack</h3>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=aws,terraform,ansible,docker,linux,git,githubactions,python,bash&theme=dark">
    <img alt="AWS, Terraform, Ansible, Docker, Linux, Git, GitHub Actions, Python, Bash" src="https://skillicons.dev/icons?i=aws,terraform,ansible,docker,linux,git,githubactions,python,bash&theme=light">
  </picture>
</p>

<p align="center">
  <sub><b>Infrastructure:</b> EC2 · VPC · ALB · Auto Scaling · ECS Fargate · S3 · CloudFront · Route 53 · ACM</sub><br>
  <sub><b>Serverless &amp; security:</b> Lambda · API Gateway · DynamoDB · Bedrock · IAM · KMS · CloudWatch</sub><br>
  <sub><b>Delivery:</b> Terraform · Ansible · Docker · Docker Compose · GitHub Actions · Jenkins · Linux · Python · Bash</sub>
</p>

<br>

<!-- PROFESSIONAL EXPERIENCE -->
<h3 align="center">Production Experience</h3>

**Web Developer Intern · Tuas Power Generation**  
April 2025 – February 2026

Delivered **three internal systems into production**, working with finance stakeholders from requirements through deployment and handover:

- **Document AI:** Built an ASP.NET service with custom Azure Document Intelligence models, processing several hundred invoices per month and returning structured JSON to internal systems.
- **Approval workflows:** Developed an ASP.NET and SQL Server application with role-based access, sequential CFO and CEO sign-off, pending queues and stored procedures.
- **Data automation:** Built a C# Excel-to-SQL Server batch tool that rejected malformed filenames and rows before they reached downstream reports.

<br>

<!-- PROJECTS -->
<h3 align="center">Selected Work</h3>

<p align="center"><sub>Self-directed projects built, deployed and documented on personal AWS accounts.</sub></p>

<table align="center">
  <tr>
    <td valign="top">
      <b>01 &nbsp;Self-Healing AWS Web Tier</b><br>
      <sub>One ALB routes three application paths to independent Auto Scaling Groups across three Availability Zones. Each group scales at 60% CPU and replaces instances that fail health checks.</sub><br>
      <sub>Configured HTTPS with ACM and Route 53, redirected HTTP to HTTPS, and documented failure testing. Security groups restrict application traffic to the ALB.</sub><br><br>
      <code>EC2</code> <code>ALB</code> <code>Auto Scaling</code> <code>VPC</code> <code>Route 53</code> <code>ACM</code><br><br>
      <a href="https://localhostshinn.xyz/blog/self-healing-auto-scaling-web-tier"><img alt="Read the web tier build and failure-testing write-up" src="https://img.shields.io/badge/WRITE--UP_%E2%86%97-57606a?style=flat-square"></a>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>02 &nbsp;Private Static Hosting with Terraform</b><br>
      <sub>Created Terraform modules for S3, CloudFront, ACM and Route 53. A private S3 origin is accessible through CloudFront Origin Access Control, with HTTPS on a custom domain.</sub><br>
      <sub>Diagnosed persistent HTTP 403 errors by tracing requests to a stale CloudFront origin path that incorrectly prefixed S3 object keys.</sub><br><br>
      <code>Terraform</code> <code>S3</code> <code>CloudFront</code> <code>OAC</code> <code>Route 53</code> <code>ACM</code><br><br>
      <a href="https://mini.shinn.life/"><img alt="View the static site" src="https://img.shields.io/badge/LIVE_%E2%86%97-24292f?style=flat-square"></a>
      <a href="https://localhostshinn.xyz/blog/s3-cloudfront-oac"><img alt="Read the S3 and CloudFront write-up" src="https://img.shields.io/badge/WRITE--UP_%E2%86%97-57606a?style=flat-square"></a>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>03 &nbsp;Containerised Portfolio &amp; Deployment Pipelines</b><br>
      <sub>Containerised a React portfolio with Docker and deployed it to ECS Fargate behind an HTTPS Application Load Balancer.</sub><br>
      <sub>Used GitHub Actions for deployment workflows; previously built a Jenkins pipeline for deployment to EC2.</sub><br><br>
      <code>Docker</code> <code>ECS Fargate</code> <code>ALB</code> <code>GitHub Actions</code> <code>Jenkins</code><br><br>
      <a href="https://localhostshinn.xyz"><img alt="View the portfolio" src="https://img.shields.io/badge/PORTFOLIO_%E2%86%97-24292f?style=flat-square"></a>
      <a href="https://github.com/Shinn0x/MyPortfolio"><img alt="View the portfolio source code" src="https://img.shields.io/badge/SOURCE_%E2%86%97-57606a?style=flat-square"></a>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>04 &nbsp;Seventy-Eight — Serverless AI Application</b><br>
      <sub>Built a React and Python tarot app with API Gateway, Lambda, DynamoDB and Amazon Bedrock. Separated fast card draws from slower AI interpretations so cards render first.</sub><br>
      <sub>Added API throttling, daily quotas and conditional writes to prevent duplicate model calls. Protected sensitive fields with KMS and wrote 13 unit tests for AWS-independent draw logic.</sub><br><br>
      <code>Python</code> <code>React</code> <code>API Gateway</code> <code>Lambda</code> <code>DynamoDB</code> <code>Bedrock</code> <code>KMS</code><br><br>
      <a href="https://seventy-eight.localhostshinn.xyz/"><img alt="Try Seventy-Eight" src="https://img.shields.io/badge/LIVE_%E2%86%97-24292f?style=flat-square"></a>
      <a href="https://localhostshinn.xyz/blog/seventy-eight-serverless-tarot"><img alt="Read the serverless application write-up" src="https://img.shields.io/badge/WRITE--UP_%E2%86%97-57606a?style=flat-square"></a>
    </td>
  </tr>
</table>

<br>

<!-- NOW -->
<h3 align="center">Now</h3>

<p align="center">
  <sub>
    ▸ Open to <b>Junior Cloud / DevOps Engineer</b> opportunities in Singapore<br>
    ▸ Designing a <b>zero-NAT VPC</b> that reaches AWS services through VPC endpoints<br>
    ▸ Sharing project builds and troubleshooting notes on <a href="https://localhostshinn.xyz">my portfolio</a>
  </sub>
</p>

<br>

<p align="center"><sub>every repo is a checkpoint.</sub></p>
