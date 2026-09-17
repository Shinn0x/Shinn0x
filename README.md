<!-- ░ HEADER: swaps with GitHub light / dark theme ░ -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=rect&color=161b22&height=140&text=Naing%20Shin%20Thant%20Zaw&fontSize=40&fontColor=f0f6fc&fontAlignY=42&desc=Junior%20Cloud%20%2F%20DevOps%20Engineer%20%C2%B7%20Singapore&descSize=15&descAlignY=70">
    <img alt="Naing Shin Thant Zaw, Junior Cloud / DevOps Engineer, Singapore" src="https://capsule-render.vercel.app/api?type=rect&color=f6f8fa&height=140&text=Naing%20Shin%20Thant%20Zaw&fontSize=40&fontColor=1f2328&fontAlignY=42&desc=Junior%20Cloud%20%2F%20DevOps%20Engineer%20%C2%B7%20Singapore&descSize=15&descAlignY=70" width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://localhostshinn.xyz"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-localhostshinn.xyz-57606a?style=flat-square&labelColor=24292f"></a>
  <a href="https://www.linkedin.com/in/naing-shin-thant-zaw/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-naing--shin--thant--zaw-57606a?style=flat-square&labelColor=24292f"></a>
  <a href="mailto:naingshinthantzaw04@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-naingshinthantzaw04@gmail.com-57606a?style=flat-square&labelColor=24292f"></a>
  <img alt="Open to work" src="https://img.shields.io/badge/Status-open_to_work-57606a?style=flat-square&labelColor=24292f">
</p>

<br>

```text
role        Junior Cloud / DevOps Engineer
based       Singapore
education   Diploma in IT, Singapore Polytechnic
internship  Tuas Power Generation, shipped a production internal web service
approach    build it on AWS, codify it in Terraform, automate the deploy
```

<br>

<!-- ░ STACK ░ -->
<h3 align="center">Stack</h3>

<p align="center">
  <code>AWS</code> &nbsp; <code>Terraform</code> &nbsp; <code>Docker</code> &nbsp; <code>Git</code> &nbsp; <code>GitHub Actions</code> &nbsp; <code>Python</code> &nbsp; <code>Bash</code>
</p>

<p align="center">
  <sub>AWS &nbsp;·&nbsp; EC2 · VPC · ALB · Auto Scaling · S3 · CloudFront · Route 53 · ACM · Lambda · API Gateway · DynamoDB · IAM · Bedrock</sub>
</p>

<br>

<!-- ░ PROJECTS ░ -->
<h3 align="center">Selected Work</h3>

<table align="center">
  <tr>
    <td valign="top">
      <b>01 &nbsp;S3 Static Site + CloudFront</b><br>
      <sub>Private S3 bucket served only through CloudFront OAC, HTTPS on a custom domain. No public bucket access.</sub><br><br>
      <code>S3</code> <code>CloudFront</code> <code>OAC</code> <code>Route 53</code> <code>ACM</code><br><br>
      <a href="https://mini.shinn.life/"><img alt="Live" src="https://img.shields.io/badge/LIVE_%E2%86%97-24292f?style=flat-square"></a>
      <a href="https://localhostshinn.xyz/blog/s3-cloudfront-oac"><img alt="Write-up" src="https://img.shields.io/badge/WRITE--UP_%E2%86%97-57606a?style=flat-square"></a>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>02 &nbsp;ALB Path Routing + Auto Scaling</b><br>
      <sub>One load balancer, three independent backends, split purely by URL path.</sub><br>
      <sub>Layer-7 rules route <code>/about-me</code> and <code>/what-am-i-doing</code> to separate backends, with everything else falling to a default target group. Each path has its own ASG across 3 AZs, scaling at 60% CPU and replacing instances that fail health checks. HTTPS terminates at the ALB via ACM + Route 53, with :80 redirected to :443.</sub><br><br>
      <code>ALB</code> <code>Auto Scaling</code> <code>EC2</code> <code>Route 53</code> <code>ACM</code><br><br>
      <a href="https://localhostshinn.xyz/blog/self-healing-auto-scaling-web-tier"><img alt="Write-up" src="https://img.shields.io/badge/WRITE--UP_%E2%86%97-57606a?style=flat-square"></a>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>03 &nbsp;Seventy-Eight</b><br>
      <sub>Serverless tarot app with AI readings. Draws cards from DynamoDB, and Bedrock explains them in plain language.</sub><br><br>
      <code>API Gateway</code> <code>Lambda</code> <code>DynamoDB</code> <code>Bedrock</code> <code>CloudFront</code><br><br>
      <a href="https://seventy-eight.localhostshinn.xyz/"><img alt="Live" src="https://img.shields.io/badge/LIVE_%E2%86%97-24292f?style=flat-square"></a>
      <a href="https://localhostshinn.xyz/blog/seventy-eight-serverless-tarot"><img alt="Write-up" src="https://img.shields.io/badge/WRITE--UP_%E2%86%97-57606a?style=flat-square"></a>
    </td>
  </tr>
</table>

<br>

<!-- ░ NOW ░ -->
<h3 align="center">Now</h3>

<p align="center">
  <sub>
    ▸ Preparing for <b>AWS Solutions Architect Associate (SAA-C03)</b><br>
    ▸ Building a multi-env <b>ECS Fargate platform</b> with Terraform + GitHub Actions<br>
    ▸ Designing a <b>zero-NAT VPC</b> that reaches AWS services through VPC endpoints
  </sub>
</p>

<br>

<p align="center"><sub>every repo is a checkpoint.</sub></p>
