# Hi, I'm Saarthak! 
I'm a passionate developer exploring **Web Development**, **Databases**, and **Artificial Intelligence**. I enjoy creating beautiful web experiences and diving into AI-related projects.

## Languages and Technologies

<p>
  <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" height="45"/>
  <img src="https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white" height="45"/>
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" height="45"/>
  <img src="https://img.shields.io/badge/-C-00599C?style=for-the-badge&logo=c&logoColor=white" height="50"/>
  <img src="https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" height="45"/>
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" height="45"/>
  <img src="https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" height="45"/><br>

  <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" height="40"/>
  <img src="https://img.shields.io/badge/-Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/-Google_Cloud-FBBB00?style=for-the-badge&logo=google-cloud&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/-Rasa-FF5C5C?style=for-the-badge&logo=rasa&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/-Canva-07B4F8?style=for-the-badge&logo=canva&logoColor=white" height="40"/>
</p>

<p>
  <a href="https://www.framer.com/">
    <img src="https://img.shields.io/badge/Framer-05F?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Badge" style="margin-right: 10px;"/>
  </a>
  <a href="https://gcap.com">
    <img src="https://img.shields.io/badge/GCAP-Certified-blue?style=for-the-badge&logo=google&logoColor=white" alt="GCAP Badge" style="margin-right: 10px;"/>
  </a>
  <a href="https://www.docker.com/">
    <img src="https://img.shields.io/badge/Docker-257bd6?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Badge" />
  </a>
</p>

###  Languages Used
import matplotlib.pyplot as plt

# Data
labels = ['Python (78%)', 'JavaScript (18%)', 'HTML (2%)', 'CSS (2%)']
sizes = [78, 18, 2, 2]

# Colors per your choice
colors = ['#00FFFF',  # cyan blue for Python
          '#FFD700',  # yellow for JS
          '#FF0000',  # red for HTML
          '#00008B']  # dark blue for CSS

# Figure with black rectangular background
fig = plt.figure(figsize=(12, 7), facecolor='black')
ax = fig.add_subplot(111)
ax.set_facecolor('black')

# Draw donut chart
wedges, texts, autotexts = ax.pie(
    sizes,
    colors=colors,
    labels=labels,          # show labels on blocks
    autopct='%1.1f%%',      # show percentage
    startangle=90,
    pctdistance=0.82,       # percentage position
    labeldistance=1.05,     # label position
    textprops={'color': 'white', 'fontsize': 12},
    wedgeprops=dict(width=0.38, edgecolor='black')
)

# Add central circle for donut effect
centre_circle = plt.Circle((0, 0), 0.62, fc='black')
ax.add_artist(centre_circle)

# Add legend
ax.legend(
    wedges, labels,
    title="Languages",
    loc="center left",
    bbox_to_anchor=(1, 0, 0.3, 1),
    facecolor='black',
    labelcolor='white'
)

# Remove axes
ax.set(aspect='equal')
ax.axis('off')

# Save chart
plt.savefig("github_languages_pie.png", dpi=300, facecolor=fig.get_facecolor(), bbox_inches='tight', pad_inches=0.4)
plt.show()

<svg width="200" height="200" viewBox="0 0 32 32">
  <!-- Python -->
  <circle r="16" cx="16" cy="16" fill="none" stroke="#3776AB" stroke-width="32" stroke-dasharray="16 80" transform="rotate(-90 16 16)"></circle>
  <!-- HTML -->
  <circle r="16" cx="16" cy="16" fill="none" stroke="#E34F26" stroke-width="32" stroke-dasharray="16 80" transform="rotate(-30 16 16)"></circle>
  <!-- CSS -->
  <circle r="16" cx="16" cy="16" fill="none" stroke="#1572B6" stroke-width="32" stroke-dasharray="16 80" transform="rotate(30 16 16)"></circle>
  <!-- JavaScript -->
  <circle r="16" cx="16" cy="16" fill="none" stroke="#F7DF1E" stroke-width="32" stroke-dasharray="16 80" transform="rotate(90 16 16)"></circle>
  <!-- React -->
  <circle r="16" cx="16" cy="16" fill="none" stroke="#61DAFB" stroke-width="32" stroke-dasharray="16 80" transform="rotate(150 16 16)"></circle>
  <!-- Rasa -->
  <circle r="16" cx="16" cy="16" fill="none" stroke="#2A2A2A" stroke-width="32" stroke-dasharray="16 80" transform="rotate(210 16 16)"></circle>
</svg>



## Connect with Me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/saarthak-kulkarni-7a355b31b)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://instagram.com/saaarthak_27)
[![HackerRank](https://img.shields.io/badge/-HackerRank-2EC866?style=flat&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/saarthakrkulkar1)

*Thanks for stopping by! Let's build something amazing*
