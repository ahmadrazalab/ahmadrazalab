<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 2rem;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1, h3 {
            color: #4CAF50;
            text-align: center;
        }
        h3 {
            color: #333;
        }
        .contact-icons a {
            margin: 0 10px;
            text-decoration: none;
        }
        .contact-icons img {
            width: 40px;
            height: 40px;
        }
        .section {
            margin: 2rem 0;
        }
        .section-title {
            font-size: 1.5rem;
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
            color: #4CAF50;
        }
        .skills, .projects, .certifications {
            display: flex;
            flex-wrap: wrap;
        }
        .skills div, .projects div, .certifications div {
            flex: 1;
            margin: 10px;
            padding: 15px;
            background-color: #e8f5e9;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .skills div h4, .projects div h4, .certifications div h4 {
            margin-top: 0;
            color: #4CAF50;
        }
        .video-embed {
            margin: 2rem 0;
            text-align: center;
        }
        .video-embed iframe {
            width: 100%;
            max-width: 640px;
            height: 360px;
            border: none;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi 👋, I'm Ahmad Raza</h1>
        <h3>A Passionate DevOps Engineer 🚀</h3>

        <div class="contact-icons">
            <a href="mailto:razahmadrsofficial@gmail.com">
                <img src="https://img.shields.io/badge/Email-razahmadrsofficial@gmail.com-blue?logo=gmail" alt="Email" />
            </a>
            <a href="https://linkedin.com/in/razahmadrsofficial">
                <img src="https://img.shields.io/badge/LinkedIn-razahmadrsofficial-blue?logo=linkedin" alt="LinkedIn" />
            </a>
        </div>

        <div class="section">
            <h3 class="section-title">About Me 🌟</h3>
            <p>I'm an experienced DevOps Engineer with a strong background in cloud technologies, containerization, and CI/CD pipelines. I specialize in optimizing infrastructure, streamlining deployments, and ensuring secure and scalable solutions for efficient software delivery.</p>
        </div>

        <div class="section">
            <h3 class="section-title">Skills & Tools 🛠️</h3>
            <div class="skills">
                <div>
                    <h4>Cloud Platforms</h4>
                    <p>AWS ☁️, Azure 🌐, Digital Ocean</p>
                    <p>EC2, CloudFront, S3, Load Balancer, AutoScaling, RDS</p>
                </div>
                <div>
                    <h4>CI/CD</h4>
                    <p>Jenkins 🔄, GitLab CI 🚀</p>
                </div>
                <div>
                    <h4>Containerization</h4>
                    <p>Docker 🐳, Kubernetes ☸️</p>
                </div>
                <div>
                    <h4>Scripting</h4>
                    <p>Bash 🖥️</p>
                </div>
                <div>
                    <h4>Operating Systems</h4>
                    <p>Linux (Ubuntu, Amazon Linux, CentOS) 🐧</p>
                </div>
                <div>
                    <h4>DNS</h4>
                    <p>Cloudflare 🌐, Route 53</p>
                </div>
                <div>
                    <h4>Version Control</h4>
                    <p>GitHub, GitLab</p>
                </div>
                <div>
                    <h4>Networking & Security</h4>
                    <p>VPN, Firewall 🔒</p>
                </div>
                <div>
                    <h4>Monitoring</h4>
                    <p>Zabbix 📊, ELK Stack 🔍</p>
                </div>
                <div>
                    <h4>Virtualization</h4>
                    <p>VMware ESXi 6.0 🖥️</p>
                </div>
            </div>
        </div>

        <div class="section">
            <h3 class="section-title">Experience 🏢</h3>
            <h4>DevOps Engineer at MCSAM (Aug 2023 - Present)</h4>
            <ul>
                <li>Deploy and manage cloud infrastructure on AWS, Azure, and Digital Ocean.</li>
                <li>Optimize cloud resources for cost efficiency.</li>
                <li>Implement CI/CD pipelines using Jenkins and GitLab CI.</li>
                <li>Automate backup operations with Bash Scripting and Crontab.</li>
                <li>Containerize applications with Docker and orchestrate with Kubernetes and EKS.</li>
                <li>Set up monitoring solutions with Zabbix and ELK for log analysis.</li>
                <li>Manage version control with GitLab.</li>
                <li>Perform production deployments using Jenkins.</li>
                <li>Implement and manage TailScale for secure access.</li>
                <li>Configure RDS Read Replica for high read requests.</li>
                <li>Utilize S3 and CloudFront for static content delivery.</li>
            </ul>

            <h4>IT Executive at WEN Energy System Pvt. Ltd (Jan 2023 - June 2023)</h4>
            <ul>
                <li>Supported IT infrastructure for 100+ users.</li>
                <li>Administered Windows and Linux servers.</li>
                <li>Set up and maintained servers and workstations.</li>
                <li>Implemented Hyper-V Linux VMs and internal chat applications.</li>
                <li>Managed Active Directory services.</li>
                <li>Configured servers and services, handled backup management and firewall policies.</li>
            </ul>
        </div>

        <div class="section">
            <h3 class="section-title">Education 🎓</h3>
            <p>Bachelor of Science - Allahabad University (2022)</p>
        </div>

        <div class="section">
            <h3 class="section-title">Projects 🛠️</h3>
            <div class="projects">
                <div>
                    <h4><a href="https://github.com" target="_blank">Kubernetes-as-Terraform</a></h4>
                    <p>Terraform configuration for deploying Kubernetes clusters on AWS.</p>
                </div>
                <div>
                    <h4><a href="https://github.com" target="_blank">AWS CLI Using Jenkins</a></h4>
                    <p>Automated app deployment using AWS CLI commands with Jenkins.</p>
                </div>
                <div>
                    <h4><a href="https://github.com" target="_blank">DevOps Stack-TodoList</a></h4>
                    <p>Infrastructure setup for automated deployment with Jenkins and various DevOps tools.</p>
                </div>
            </div>
        </div>

        <div class="section">
            <h3 class="section-title">Certifications 🎓</h3>
            <div class="certifications">
                <div>AWS Certified Solution Architect - Associate</div>
                <div>Microsoft Certified Azure Fundamentals AZ-900</div>
                <div>AWS Certified Cloud Practitioner</div>
                <div>Redhat Certified System Administrator</div>
                <div>Jetking Certified Network Engineer</div>
            </div>
        </div>

        <div class="video-embed">
            <h3 class="section-title">Videos 📹</h3>
            <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" title="Video Embed" allowfullscreen></iframe>
        </div>

    </div>
</body>
</html>
