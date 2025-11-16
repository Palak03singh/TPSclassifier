# TPSclassifier
TPSclassifier is a self-contained, cross-platform Python application for the functional subfamily classification of terpene synthases (TPSses), widely applicable across Viridiplantae taxonomy. The tool is optimized for high-throughput analysis of large FASTA datasets via encrypted threaded execution. Its core prediction mechanism utilizes adaptive motif extraction and compositional encoding specifically tuned for TPS domains. It offers dual functionality for diverse workflow integration:
•	**GUI Mode:** A lightweight interface requiring no command-line proficiency.
•	**Script Mode:** Direct invocation from the terminal, enabling pipeline integration and batch processing.
# **Functional Overview:**
The tool accepts protein FASTA sequences as input. Upon submission, it automatically pre-processes and encodes the sequences using optimized protein descriptors and motif-based features, applies pre-trained Random Forest classification model, generating structured output files containing predicted TPSes in excel and fasta, static and interactive PCA plots for summary visualizations.
Platform Compatibility:
** Operating Systems: Linux (Ubuntu) and Windows (10)**
# **Example Usage to launch GUI mode:**
Double click on “app.exe” file for GUI Mode or paste the command within the dist folder to launch “python TPSclassifier.py”
→ Launches the graphical interface where users can browse for input/output and specify thread count.
# **Command Line Mode**
  python TPSclassifier.py -i input.fasta -o results/ -t 8
  → Runs classification directly via terminal with 8 threads.
# **Technical support:**
Email to – palak03singh@gmail.com, fkhan.cimap@csir.res.in 
# **Referencing:**
Currently no manuscript is available to cite for this tool, instead you can cite the link directly as “Singh, P. and Khan, F. https://github.com/Palak03singh/TPSclassifier"
