# car-price-prediction
New_Price feature dropped due to significant missing values.
Name column split into Brand and Model features.
Continuos variables including target feature are Log transformed to make their distribution symetrical.
Kilometers_Driven and Mileage are multiplied together to form new feature as this interaction show high correlation with target feature price.
Brand,Model, and Location are encoded using Target encoding as they have lot of categories.
Fuel_Type, Transmission, and Owner_Type are one-hot encoded.
Year columns are deducted by current year to introduce aging effect (current year - edition year).
