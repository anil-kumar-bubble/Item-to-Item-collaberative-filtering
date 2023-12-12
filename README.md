
<h1>Item-Item Collaborative filtering:</h1>
<h4></i>Let ‘x’ be the product that we need to determine the rating that will be given by the user based on ratings given to similar products by the user.
Let ‘n’ be similar products that are present in user’s past order data.
Then to find the rating of ‘x’ product is
  x_r_u_i_new = (sim(i_new, i_1) * r_ui_1 + sim(i_new, i_2) * r_ui_2 + ... + sim(i_new, i_n) * r_ui_n) / (sim(i_new, i_1) + sim(i_new, i_2) + ... + sim(i_new, i_n))
Here, "r_u_i" are the ratings that the user "u" has given to similar items, and "sim(i_new, i_i)" is the similarity between the new product and each past product.
based on ratings rank will be assigned
Top-ranked products will be recommended first</h4>
Hi
 


