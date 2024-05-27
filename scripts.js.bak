document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Thank you for your message!');
    this.reset();
});

// Dynamic loading of projects
document.addEventListener('DOMContentLoaded', function() {
    const projects = [
        {
            title: "Network Optimization Project",
            description: "Developed a comprehensive network optimization strategy for a medium-sized enterprise. Utilized tools like Wireshark and Cisco Packet Tracer to analyze network performance and implement improvements, resulting in a 25% increase in data throughput."
        },
        {
            title: "Cloud Migration",
            description: "Led a cloud migration project for a large organization, transitioning services from on-premises servers to AWS. The project improved scalability and reduced costs by 30%."
        },
        // Add more projects as needed
    ];

    const projectSection = document.getElementById('projects');
    projects.forEach(project => {
        const projectDiv = document.createElement('div');
        projectDiv.className = 'project';
        
        const projectTitle = document.createElement('h3');
        projectTitle.textContent = project.title;
        projectDiv.appendChild(projectTitle);
        
        const projectDesc = document.createElement('p');
        projectDesc.textContent = project.description;
        projectDiv.appendChild(projectDesc);
        
        projectSection.appendChild(projectDiv);
    });
});
