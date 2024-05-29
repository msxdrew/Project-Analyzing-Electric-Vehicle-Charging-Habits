As electronic vehicles (EVs) become more popular, there is an increasing need for access to charging stations, also known as ports. To that end, many modern apartment buildings have begun retrofitting their parking garages to include shared charging stations. A charging station is shared if it is accessible by anyone in the building.

EV Charging
But with increasing demand comes competition for these ports — nothing is more frustrating than coming home to find no charging stations available! In this project, you will use a dataset to help apartment building managers better understand their tenants’ EV charging habits.

The data has been loaded into a PostgreSQL database with a table named charging_sessions with the following columns:

charging_sessions
Column	Definition	Data type
garage_id	Identifier for the garage/building	VARCHAR
user_id	Identifier for the individual user	VARCHAR
user_type	Indicating whether the station is Shared or Private	VARCHAR
start_plugin	The date and time the session started	DATETIME
start_plugin_hour	The hour (in military time) that the session started	NUMERIC
end_plugout	The date and time the session ended	DATETIME
eng_plugin_hour	The hour (in military time) that the session ended	NUMERIC
duration_hours	The length of the session, in hours	NUMERIC
el_kwh	Amount of electricity used (in Kilowatt hours)	NUMERIC
month_plugin	The month that the session started	VARCHAR
weekdays_plugin	The day of the week that the session started	VARCHAR
Let’s get started!

Sources
Data: CC BY 4.0, via Kaggle,
Image: Julian Herzog, CC BY 4.0, via Wikimedia Commons
