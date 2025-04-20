# Parkinson’s Patient Similarity Graph Analysis using GraphFrames

This project explores Parkinson's telemonitoring data by modeling patient similarity as a graph using Apache Spark and GraphFrames. Patients are connected based on similar motor UPDRS scores to discover influential patients and communities.

## 🩺 Project Highlights

- Constructs a graph where nodes represent patients.
- Edges connect patients with motor_UPDRS scores differing by less than 2.
- Applies PageRank to identify influential patients.
- Merges graph results with patient metadata (age, sex).
- Visualizes patient similarity network with NetworkX.

## 🧪 Technologies Used

- Python
- Apache Spark
- GraphFrames
- Pandas
- NetworkX
- Matplotlib

## 🚀 Getting Started

1. Download the dataset: `parkinsons_telemonitoring.csv`
2. Install required packages:
   ```bash
   pip install pandas matplotlib networkx
3. Run the notebook with:
   ```bash
   pyspark --packages graphframes:graphframes:0.8.4-spark3.5-s_2.12

## 📂 Dataset

- Parkinson’s Telemonitoring dataset
- Includes motor_UPDRS scores, age, and sex of patients

## 📈 Example Outputs

- PageRank-based patient influence rankings
- Network graph of similar patients
- Metadata-joined graph metrics

## 📄 License

This project is open source and available under the MIT License.
