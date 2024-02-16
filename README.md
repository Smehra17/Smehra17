- 👋 Hi, I’m @Smehra17
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Smehra17/Smehra17 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Sample data sheet (replace this with the actual data provided by the instructor)
data_sheet = [
    ("Smith", 2, 3),
    ("Johnson", 3, 2),
    ("Williams", 4, 1),
    # Add the remaining elements here
]

# Initialize variables to store the totals
total_adults = 0
total_children = 0

# Calculate totals
for family_name, adults, children in data_sheet:
    total_adults += adults
    total_children += children

# Calculate total adults and children together
total_adults_children_together = total_adults + total_children

# Print the results
print("Total number of adults:", total_adults)
print("Total number of children:", total_children)
print("Total number of adults and children together:", total_adults_children_together)
