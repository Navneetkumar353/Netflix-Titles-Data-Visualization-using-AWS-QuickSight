# Netflix Titles Analytics with Amazon QuickSight

## **Project Overview**
This project focuses on visualizing and analyzing Netflix titles using **Amazon QuickSight**. The dataset used includes information about movies and TV shows available on Netflix, categorized by release year, genre, and other attributes.

## **Dataset**
- **Source**: The dataset (`netflix_titles.csv`) was uploaded to an **Amazon S3 bucket** and connected to QuickSight.
- **Data Attributes**:
  - Title
  - Type (Movie/TV Show)
  - Release Year
  - Genre
  - Date Added

## **Project Steps**
### 1️⃣ **Uploading Data to Amazon S3**
- Uploaded `netflix_titles.csv` and `manifest.json` to an S3 bucket.
- Edited the `manifest.json` file to update the S3 URI for correct data mapping.

### 2️⃣ **Connecting S3 to Amazon QuickSight**
- Created a **QuickSight** account.
- Connected QuickSight to the **S3 bucket** under **Manage Data Sources**.
- Granted necessary permissions to import the dataset.

### 3️⃣ **Data Visualization**
- **Movies vs. TV Shows Breakdown**:
  - Plotted the **number of movies vs. TV shows** by release year.
- **Genre Analysis (Post-2015)**:
  - Focused on **Thrillers, TV Comedies, and Action & Adventure**.
  - Filtered out titles released before 2015.
- **Title Additions Over Time**:
  - Visualized the number of new titles added to Netflix per year.

### 4️⃣ **Using Filters**
- Applied filters to **exclude movies and TV shows before 2015**.
- Created clear **dashboard titles** to improve visualization clarity.

## **Key Learnings**
- **Importance of `manifest.json`**: Crucial for correctly mapping S3 data to QuickSight.
- **Data Filtering & Insights**: Filtering data before 2015 improved focus on modern trends.
- **QuickSight Dashboard Setup**: Titles and filters help in making dashboards **more intuitive**.

## **Project Duration**
- The project took **~2 hours** to complete, including **data upload, connection, and visualization**.

## **References**
- **Amazon QuickSight Documentation**: [AWS QuickSight Docs](https://docs.aws.amazon.com/quicksight/)
- **Project Guide**: [NextWork Project Page](https://community.nextwork.org/c/i-have-a-question?automatic_login=true)


