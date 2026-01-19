# tk-auto-posting-tool Documentation

## Introduction to MadHub's Powerful Features

MadHub's powerful automation features leverage advanced Android APIs to enable seamless content scheduling across various social media platforms. For the **tk-auto-posting tool**, this capability is vital, allowing users to automate post management efficiently. With MadHub, users can schedule posts, manage content publication, and expand their social media presence without manual intervention.

## Technical Capabilities

### 1. Facebook Group Auto-Posting
The **Facebook Group Auto-Posting** feature allows users to automatically execute posting tasks across multiple joined groups. This feature empowers users to manage their content strategically while maximizing reach and engagement. 

- **Content Rotation and Loop Mode**: Users can configure their posts to rotate or loop, ensuring diverse content presentation and sustained engagement.
- **Content Formatting Options**: This feature supports both simple text input and file uploads, allowing users to utilize images and formatted content effectively.

### 2. Facebook Auto-Post
The **Facebook Auto-Post** feature provides a streamlined approach to publishing content directly on the user’s personal homepage or within specific groups. This feature helps maintain consistent account activity and boosts visibility.

- **Visibility Options**: Users can decide on the visibility of their posts, choosing between public, friends-only, or group settings.
- **Advanced Scheduling**: Users can set the operation interval, specify the number of posts, and configure wait times between posts, providing flexibility in content management.

### 3. Instagram Auto-Reply
The **Instagram Auto-Reply** feature enhances user interaction by automatically responding to unread messages. This functionality is essential for maintaining customer engagement and ensuring timely communication.

- **Message Management**: Users can set custom replies and configure the option to delete messages after they’ve been sent, ensuring a clean inbox and focused interactions.
- **Interval Configuration**: Customizable operation intervals and run durations allow users to manage the speed and frequency of their auto-responses effectively.

## Usage Instructions

### Facebook Group Auto-Posting
1. **Setup**:
   - Navigate to the **Facebook Group Auto-Posting** section in MadHub.
   - Select the groups where you wish to post.

2. **Content Input**:
   - Choose between **Input Mode** (typing directly) or **File Mode** (uploading a pre-prepared document).
   - For image posts, ensure the images are uploaded accordingly.

3. **Post Configuration**:
   - Specify the total post count and set how many times each post should be published in a loop.
   - **Content Rotation**: Enable this feature to rotate between different posts automatically.

### Facebook Auto-Post
1. **Configuration**:
   - Access the **Facebook Auto-Post** feature in the dashboard.
   - Input the content you wish to post or upload files as needed.

2. **Visibility Settings**:
   - Choose the visibility option: Public or Friends Only.
   - Specify the posting intervals, total post count, and wait time.

3. **Execution**:
   - Schedule the start time for the posts. 
   - Activate the posting feature to begin automating your content.

### Instagram Auto-Reply
1. **Access the Feature**:
   - Go to **Instagram Auto-Reply** in the MadHub interface.

2. **Message Configuration**:
   - Create the default message that will be sent in response to incoming messages.
   - Enable the option to delete the message after sending, if necessary.

3. **Set Intervals**:
   - Configure the operation interval (how often the replies are sent) and the single run duration (how long the feature will be active).

## Configuration Examples

### Facebook Group Auto-Posting Configuration
To set up **Facebook Group Auto-Posting**, follow these steps:
```json
{
  "groups": ["Group1", "Group2"],
  "mode": "file", // file or input
  "postCountPerGroup": 3,
  "totalPostCount": 10,
  "contentRotation": true
}
```

### Facebook Auto-Post Configuration
For **Facebook Auto-Post**, you might configure it like this:
```json
{
  "content": "Check out our new product!",
  "visibility": "public", // or "friends"
  "operationInterval": 30, // in minutes
  "singlePostCount": 5,
  "postWaitTime": 10 // seconds between posts
}
```

### Instagram Auto-Reply Configuration
For **Instagram Auto-Reply**, configure the feature with:
```json
{
  "autoReplyMessage": "Thank you for your message! We'll get back to you shortly.",
  "deleteAfterSending": true,
  "operationInterval": 5, // seconds
  "singleRunDuration": 120 // seconds
}
```

## Conclusion

MadHub provides robust features tailored for social media management, particularly through its **Facebook Group Auto-Posting**, **Facebook Auto-Post**, and **Instagram Auto-Reply** functionalities. By leveraging these powerful automation features and adjusting technical configurations, users can efficiently manage their online presence and enhance engagement with their audience. With MadHub, content scheduling becomes a streamlined process, allowing users to focus on creating quality content while the system handles the rest.
