# The Ethnicity Harmonization Project

## Overview
The Ethnicity Harmonization Project aims to enhance the quality and comparability of ethnicity data across different countries, focusing initially on African nations. By harmonizing ethnicity variables, we can improve the accuracy and utility of socioeconomic data, thereby supporting better policy-making for vulnerable groups.

## Encrypted Scripts
All Stata scripts in this repository are encrypted using GPG4WIN software to protect sensitive components of the project. These scripts are not publicly available in their readable form. Users interested in accessing the encrypted scripts must contact the project creators, Paola Ballon (pballon@worldbank.org) and/or Omar Alburqueque (oalburquequchav@worldbank.org), to request access. Permission will be granted at the discretion of the creators, based on the provided purpose for their use. For more details, see the [LICENSE.md](LICENSE.md) file.

## Motivation
The need for disaggregated data for vulnerable groups, such as ethnic groups, is critical for linking data to poverty reduction efforts. The World Bank Group's Scorecard FY24-FY30 emphasizes the development of disaggregated metrics to foster insights supporting these groups. The lack of a universal definition of ethnicity and its varied operationalization in research complicates its measurement and comparability across studies.

## Project Goals
The primary goal is to disaggregate socioeconomic information by ethnic groups using microdata from the Global Monitoring Database (GMD). This pilot project focuses on African countries, successfully harmonizing ethnicity data across 11 countries: Benin, Burkina Faso, Côte d'Ivoire, Gabon, Ghana, Guinea, Gambia, Guinea-Bissau, Senegal, Togo, and South Africa.

## Methodology
We employ a frequentist approach to harmonize ethnicity, starting with the distribution of ethnic groups within each country. This involves:
- **Top 3 Classification**: Identifying the three largest ethnic groups by population, with a 'residual' category for all other groups.
- **Top 5 Classification**: Identifying the five largest ethnic groups by population, with a 'residual' category for all other groups.

Our harmonization approach involves recoding data specific to each survey and country, complementing existing methods of capturing ethnicity in household surveys without standardizing the variable across countries.

## Benefits
- **Minimizing Bias**: Our framework categorizes based on population size, reducing subjective bias related to ethnic identity and politics.
- **Standardized Comparisons**: A harmonized ethnicity variable standardizes comparisons across surveys, enhancing insights into demographic trends and social changes.
- **Ethical Commitment**: Retaining the original ethnicity variable alongside harmonized categories improves visibility and balances discrimination risks.
- **Stakeholder Engagement**: Clear categorization criteria improve transparency and facilitate research approvals.

## Challenges
- **Survey Limitations**: Our work relies on surveys representative at the national level and, at most, the ADM1 subnational level, which may underrepresent some ethnic groups.
- **Complexity of Ethnicity**: Ethnicity is a multifaceted and evolving concept. For practical reasons, our methodology confines ethnicity to self-identification, aligning with household survey measurements.

## Support
For questions or assistance, please open an issue in this repository or contact Paola Ballon (pballon@worldbank.org) and/or Omar Alburqueque (oalburquequechav@worldbank.org).

## Contributing
We welcome contributions to improve the replication process. If you have suggestions, please open an issue or submit a pull request.
