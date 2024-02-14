create or replace view CUSTOMER_LOYALTY_METRICS_V(
	CUSTOMER_ID,
	CITY,
	COUNTRY,
	FIRST_NAME,
	LAST_NAME,
	PHONE_NUMBER,
	E_MAIL,
	TOTAL_SALES,
	VISITED_LOCATION_IDS_ARRAY
) COMMENT='Tasty Bytes Customer Loyalty Member Metrics View'
 as
SELECT * FROM frostbyte_tasty_bytes.harmonized.customer_loyalty_metrics_v;