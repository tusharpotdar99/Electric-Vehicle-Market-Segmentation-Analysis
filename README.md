# Electric Vehicle Market Analysis

## Overview

This project presents a comprehensive analysis of India's electric vehicle market, focusing on segmentation derived from sales data, customer reviews, and technical specifications. The goal is to strategically position an electric vehicle startup in the Indian market by utilizing data-driven insights to identify and target optimal market segments.

## Project Highlights

- **Market Segmentation:** Employing k-means clustering to identify distinct market segments based on customer reviews and technical specifications.
- **Data Sources:** Sales data from the Society of Manufacturers of Electric Vehicles, customer reviews from bikewale.com, and technical specifications from the same source.
- **Technical Analysis:** Examination of price ranges, riding ranges, top speeds, weights, and battery charging times across different segments.
- **Target Segmentation:** Identification of Segment 1 and Segment 2 as key market targets with specific technical specifications and price ranges tailored to their needs.

## Data Sources

1. **Sales Data:** Provided by the Society of Manufacturers of Electric Vehicles (2017-2023). Includes sales figures for electric two-wheelers, three-wheelers, four-wheelers, and buses.
2. **Customer Reviews:** Extracted from bikewale.com, offering insights into consumer behavior and psychographic data.
3. **Technical Specifications:** Detailed data on electric two-wheelers, including pricing and performance metrics.

## Data Pre-processing

- **Merging Datasets:** Combined sales data from multiple Excel sheets into a unified dataset using pandas.
- **Data Aggregation:** Performed aggregation operations to understand market trends.
- **Handling Null Values:** Managed missing data to ensure a complete dataset.
- **Sentiment Analysis:** Conducted using NLTK to gain qualitative insights into customer sentiment.

## Market Segmentation Analysis

- **Algorithm:** K-means clustering was applied to identify market segments.
- **Optimal Segments:** Identified Segment 1 and Segment 2 as the most promising for targeting.
- **Technical Specifications:** Defined recommended specifications for Segment 1 to align with market needs.

## Target Segment Recommendations

- **Segment 1:** 39% of consumers. Key characteristics include a broad range of technical specifications and price points.
- **Segment 2:** 33% of consumers. Emphasizes visual appeal, reliability, and value for money.

## Technical Specifications for Segment 1

| **Specification**        | **Recommended Range**         |
|--------------------------|-------------------------------|
| **Price**                | ₹70,688 – ₹1,29,063           |
| **Riding Range**         | 89 - 180 km                   |
| **Top Speed**            | 58 - 116 kmph                 |
| **Weight**               | 76 - 120 kg                   |
| **Battery Charging Time**| 3 - 5 hours                  |
| **Rated Power**          | 1200 - 5500 W                 |

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/electric-vehicle-market-analysis.git
