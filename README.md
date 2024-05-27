# Homology_Modeling_Using_Modeller
🌟Unveiling a New Protein Model for Hepatitis C Virus NS3 Protease Genotype 3🦠

I am thrilled to share the culmination of a recent bioinformatics project focused on modeling the 3D structure of the NS3 protease of Hepatitis C Virus (HCV) genotype 3, a variant reported from Pakistan. This particular protein's 3D structure isn't available in the PDB database, posing a unique challenge and opportunity.

Here's a detailed overview of the process:

🔍 **Sequence Retrieval**: The protein sequence was sourced from the NCBI database, ensuring we started with accurate and up-to-date information.

💡 **Template Selection**: Utilizing BLAST, I identified four similar protein sequences as templates, specifically those with PDB IDs: 6P6S, 6P6V, 3P8N, and 4I31. These templates provided a solid foundation for building our model.

🛠️ **Model Generation with Modeller 10.5**: Through several meticulous steps, including:
- Creating *.ali file
- Overwriting *.py script files
- Selecting the optimal template (6P6S)
I generated four distinct 3D structures of the query sequence.

📊 **Evaluation and Optimization**: Among the four generated structures, one stood out with a significantly lower DOPE score of -14525.81543, indicating higher accuracy and stability.

🔬 **Verification with Biovia Discovery Studio**: To ensure the reliability of our model, I conducted a thorough comparison between the selected template structure and the generated 3D structure of the query sequence, confirming the alignment and similarity.

This comprehensive approach not only enhances our understanding of HCV genotype 3 NS3 protease but also paves the way for further research and potential therapeutic developments.
