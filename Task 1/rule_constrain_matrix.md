ID	    Rule	                                          Enforcement
BR-01	Every customer has a unique ID	                  PRIMARY KEY
BR-02	Every order has a unique ID	                      PRIMARY KEY
BR-03	Every order references an existing customer       FOREIGN KEY
BR-04	Order status must be PLACED, PAID, or CANCELLED	  CHECK
BR-05	Order amount must not be negative	              CHECK