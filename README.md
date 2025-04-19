# MyFirstApp-Streamlit
# 🚕 Uber Pickups in NYC — Streamlit App

This is a simple **Streamlit** application that visualizes Uber pickups in New York City, based on public data.  
It demonstrates the basics of data loading, caching, user interaction, and visualizations using maps and charts.

---

## 📸 App Preview

```mermaid
graph TD
    A[Streamlit App] --> B[Load Uber Data]
    B --> C[Display Raw Data (Optional)]
    B --> D[Histogram: Pickups by Hour]
    B --> E[Map: All Pickups]
    E --> F[Map: Pickups at Selected Hour]

