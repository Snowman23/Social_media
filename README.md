# Social Media Analytics Dashboard – Power BI

## Project Overview
This project showcases an interactive **Power BI dashboard** built on top of a social media database managed with **Oracle APEX**. It provides insights into user behavior, content engagement, and community interactions by visualizing multiple interconnected tables: Users, Posts, Comments, Likes, Followers, Messages, and Notifications.

The data is accessed directly from **RESTful JSON endpoints** exposed by Oracle APEX, ensuring real-time synchronization with the database.

---

## Data Source
- Oracle APEX RESTful Services provide live access to all tables in JSON format.
- Tables visualized include:
  - **Users**: Profiles, join dates, verification status
  - **Posts**: Content, media, visibility, engagement metrics
  - **Comments**: Comment content, likes
  - **Likes**: Likes on posts and comments
  - **Followers**: Relationships between users
  - **Messages**: Sent/received messages
  - **Notifications**: User activity notifications

---

## Dashboard Design & Visualizations

### User Engagement
- **Posts per User** – Bar chart showing the number of posts each user has published.
- **Likes per Post** – Column chart aggregating likes for each post.
- **Comments per Post** – Column chart displaying comment count by post.

### Content Distribution
- **Post Visibility** – Pie chart showing Public, Friends Only, and Private posts distribution.
- **Media Types** – Donut chart showing proportion of posts with images, videos, or text only.

### Community & Interaction
- **Followers Network** – Table and matrix visualizations showing follower relationships.
- **Messages Overview** – Table summarizing messages sent and received per user.
- **Notifications Activity** – Bar chart summarizing types of notifications (Like, Comment, Follow, Mention).

### Time-Based Analysis
- **Posts Over Time** – Line chart showing posting trends over time.
- **User Activity Timeline** – Line or area chart showing engagement metrics like likes, comments, and posts per day/week.

---

## Key Features
- **Live Data Integration**: RESTful API ensures dashboards update automatically when the database changes.
- **Cross-Filtering**: Interconnected visuals allow filtering across users, posts, comments, and engagement metrics.
- **Aggregated Insights**: Measures such as total posts, likes, and comments per user provide actionable metrics.
- **Interactive Design**: Users can explore content, followers, and notifications dynamically.

---

## Skills Demonstrated
- Advanced **Power BI dashboard design** and data visualization.
- **RESTful API integration** with Oracle APEX.
- Data modeling of relational social media tables.
- Creation of **interactive and dynamic dashboards** for real-time insights.
