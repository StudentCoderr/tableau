# tableau
# Customer Personality Analysis (Tableau Dashboard)
# Customer Personality Analysis Dashboard

**A comprehensive data analysis and visualization project designed to segment customers based on their personality profiles, habits, and household traits. This dashboard enables businesses to transition from generic marketing strategies to highly targeted, data-driven campaigns.**

---

## 🛠️ Data Preparation & Feature Engineering

### 1. Data Cleaning
*   **Handle Missing Values:** Identified and addressed missing data points (such as incomplete entries in the `Income` column) via target imputation or exclusion to ensure data integrity.
*   **Feature Engineering:** Developed calculated fields to extract deeper insights:
    *   **Age:** Derived directly from `Year_Birth`.
    *   **Total Spent:** Aggregated spending across all product categories (`MntWines`, `MntMeatProducts`, etc.).
    *   **Total Children:** Combined `Kidhome` and `Teenhome` variables.
    *   **Enrollment Years:** Calculated based on the `Dt_Customer` timestamp.

### 2. Data Loading & Relationship Setup
*   **Tableau Connection:** Integrated the processed `marketing_campaign.csv` dataset into **Tableau**.
*   **Schema Verification:** Validated data types to ensure Tableau correctly distinguishes dimensions from continuous measures (e.g., configuring `ID` as a string dimension and `Income` as a continuous measure).

---

## 📊 Exploratory Data Analysis (EDA)

The analysis is divided into dedicated worksheets to isolate and evaluate specific business questions:

*   **Demographic Profile:** Utilizes histograms and bar charts to evaluate the distribution of `Education`, `Marital Status`, and `Age` groups against `Income`.
*   **Spending Behavior:** Employs packed bubble charts and stacked bar charts to highlight revenue-generating product categories.
*   **Channel Efficiency:** Features side-by-side bar charts comparing customer purchasing preferences (**Web** vs. **Catalog** vs. **Store**).
*   **Campaign Success Rate:** Maps out conversion metrics across **Campaigns 1 through 5** using highlighted tables and dual-axis charts.

---

## 🎨 Dashboard Design & Interactivity

*   **Unified Layout:** Consolidated individual sheets into a clean, intuitive dashboard layout optimized for standard desktop resolutions (**1000x800**).
*   **Global Filters:** Implemented dynamic filtering for `Education`, `Marital Status`, and `Age Group` to allow stakeholders to slice data seamlessly.
*   **Dashboard Actions:** Configured interactive actions where selecting a specific customer segment automatically filters product spending and channel breakdowns.
*   **Visual Polish:** Removed distracting gridlines and applied a professional, cohesive color palette to maximize readability.

---

## 📈 Key Insights & Conclusion

*   **High-Value Segments:** High-income, highly-educated customer segments contribute the highest share of overall revenue, showing a strong preference for **Wine** and **Meat** products.
*   **Channel Optimization:** While physical stores maintain a consistent baseline traffic volume, **Web** and **Catalog** channels scale significantly higher among premium-tier buyers.
*   **Campaign Conversion:** Early marketing campaigns show varied engagement, with a distinct spike in acceptance rates when promotions are tailored precisely to matching demographic and income brackets.

**Conclusion:** This analytical framework demonstrates that marketing efficiency increases dramatically when product offerings and promotional campaigns are personalized to specific consumer personas rather than broad distributions.

---

## 🚀 How to View the Dashboard

To explore the interactive visualizations locally:
1. **Download** the `customer personality analysis.twbx` file from this repository.
2. **Install** [Tableau Desktop](https://www.tableau.com/) or [Tableau Public](https://public.tableau.com/) (Free).
3. **Open** the `.twbx` file within Tableau to interact with the filters, actions, and visualizations.

---

## 📬 Contact Information

*   **Developer:** Poornashree J P  
*   **Repository:** [StudentCoderr/tableau-](https://github.com/StudentCoderr/tableau-)
