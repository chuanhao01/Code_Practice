Business is booming at Big Bill’s Burger Shack. Bill sells the most convenient, customizable burger in town. Using either the shack’s website or mobile application, customers can request patties that are prepared precisely to the second. The i-th order consists of two integers: di, the amount of time each side of the patty should be cooked and ti, the exact time at which the customer would like to pick up their order.

Big Bill is a talented grill cook, and he only hires talented grill cooks. In a given second, a grill cook can use a hand to do at most one of the following:

place a new patty on the grill,

flip a patty that is already on the grill,

remove a patty from the grill to serve it to a customer, or

do nothing.

Each grill cook has two hands, so they can do up to two of the above actions in a second.

When a patty is placed or flipped on the grill, the side on the grill immediately starts cooking. For example, if a patty is placed on the grill at 500 seconds, flipped at 600 seconds, and removed at 700 seconds, then it has cooked 100 seconds on each side.

These customers are demanding — they want to be served exactly at ti, and the patty must be cooked for exactly di seconds on each side. Once a patty is on the grill, it must not be taken off until the customer wants it served. Orders that are not prepared exactly to the customers’ specifications would ruin Big Bill’s reputation. However, he doesn’t want to hire more grill cooks than he needs to. What is the minimum number of grill cooks needed to serve all the orders?

Input
The first line contains a single integer 1≤n≤100, the number of orders for Big Bill’s patties. The next n lines each contain two integers, di and ti. This means that the i-th patty should be cooked for exactly di seconds on each side and needs to be served exactly at time ti. It is guaranteed that 1≤di≤600, 2≤ti≤43200, and that it is possible to cook every order to specification without taking an action before second 0.

Output
Output a single integer, the minimum number of cooks needed to prepare all of the orders.