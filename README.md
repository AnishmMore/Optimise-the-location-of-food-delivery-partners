# Optimise-the-location-of-food-delivery-partners

If the map is not showing properly on GitHub, you can try running the file on Google Colab. To do this, look for the **"Open in Colab"** button on the top right corner of the file on GitHub. Clicking this button will open the file in Google Colab, where you can run the code and view the map properly.

**Main idea:**

My main idea is to use Geopandas and OpenStreetMap to optimize the location of food delivery partners. By analyzing the density of restaurants in different areas, I can identify areas with a high concentration of restaurants and recommend that food delivery partners be positioned in these areas. This can increase the chance of food delivery pickups and improve the efficiency of the delivery service.

**Analysis:**

When we add a half mile buffer around each of our restaurants, we can better determine where these buffers overlap (for example, locations within range of more than one restaurant will appear more opaque)

**Results:**

<img width="1307" alt="Screenshot 2022-12-09 at 2 49 20 PM" src="https://user-images.githubusercontent.com/57623274/206808325-ed8746f5-79f1-4de2-88b6-1cf4640e3dcb.png">

Overall, the blue dot on the map represents an optimal location for food delivery partners in Riverside, based on the availability of restaurants and the accessibility of the area. By positioning food delivery partners in this location, the chances of successful food delivery pickups can be increased and the efficiency of the delivery service can be improved.


