# Superset Dashboards Repository

This repository contains exported dashboards from Apache Superset.  
It includes JSON/YAML files that can be imported into another Superset instance for analysis or sharing.

## 📁 Structure

- `dashboards/` — folder with exported dashboards in JSON/YAML format  
  - `customers_dashboard.json` — Dashboard showing customer metrics, top cities, and other visualizations  
  - `sales_heatmap.json` — Heatmap showing sales distribution  
  - `treemap.json` — Treemap for product categories  
  - (Add more exported dashboards here)

- `README.md` — this file  

## ⚡ How to Import Dashboards

1. Open your Superset instance.  
2. Go to **Dashboards → + Dashboard → Import Dashboard**.  
3. Choose the JSON/YAML file from the repository.  
4. Click **Import**. The dashboard will appear in Superset.

## 📝 Notes

- Dashboards were created using the `olist_customers_dataset` and `olist_orders_dataset`.  
- Some calculated columns, metrics, and filters are included in the exported files.  
- You can edit or update the dashboards directly in Superset after import.  

## 🔗 References

- [Superset Documentation](https://superset.apache.org/docs/intro)  
- [GitHub](https://github.com)
