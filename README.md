# Instagram Followers Analyzer

A simple web application that helps you identify people who don't follow you back on Instagram by analyzing your Instagram data export.

## Features

-**Find Non-Followers**: Quickly identify accounts you follow that don't follow you back
-**Statistics Dashboard**: View your total following, total followers, and non-followers count
-**Search & Filter**: Search through profiles by username and sort by date or alphabetically


## How to Use

### Step 1: Export Your Instagram Data

1. Go to your Instagram account settings
![Export Information](/Screenshots/1.png)
2. Navigate to "Your activity" → "Download your information"
3. Select "JSON" format
![Export Information](/Screenshots/2.png)
4. Request a download of your data
5. Once downloaded, extract the ZIP file

### Step 2: Locate the Required Files

You'll need these two files from your Instagram data export:
- `following.json` - Located in `followers_and_following/following.json`
- `followers_1.json` - Located in `followers_and_following/followers_1.json`

### Step 3: Open the Application

1. Open `not_following_back.html` in your web browser
2. Click "Choose File" for the **Following File** and select your `following.json`
3. Click "Choose File" for the **Followers File** and select your `followers_1.json`
4. Click the **"Process Files"** button

### Step 4: View Results

The application will:
- Display statistics showing how many people you follow, how many follow you, and how many don't follow back
- Show a list of all profiles that don't follow you back
- Allow you to search and filter through the results
- Provide direct links to each profile on Instagram

## Troubleshooting

### "Failed to fetch" Error
- Make sure you're selecting the correct JSON files
- Ensure the files are valid JSON format
- Try refreshing the page and selecting the files again

### No Results Showing
- Verify that both files are selected before clicking "Process Files"
- Check that the files are from a recent Instagram data export
- Ensure the file structure matches Instagram's export format

### Files Not Loading
- Make sure the JSON files are not corrupted
- Try re-downloading your Instagram data export
- Check that you're selecting the correct files (following.json and followers_1.json)

## Notes
- This is a personal utility tool. Feel free to use and modify as needed.
- The application processes data locally in your browser
- Large follower lists may take a few seconds to process
- Results are based on the data in your Instagram export at the time of export
- Instagram data exports may take 24-48 hours to generate

---

**Enjoy analyzing your Instagram connections!** 

