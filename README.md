=IF(AND(L14="O", OR(LEFT(L14,5)="VEC00",LEFT(L14,5)="VEE01",LEFT(L14,5)="VFA01"), K14="0000"), "O", "X5")
=IF(AND(J35="TYD01EJB.jar",OR(LEFT(I35,5)="VEC00",LEFT(I35,5)="VEE01",LEFT(I35,5)="VFA01"),K35="2024-02-16 14:03:02 JST Java6"),"o","X5")


=IF(AND(J35="TYD01EJB.jar", OR(LEFT(I35,5)="VEC00", LEFT(I35,5)="VEE01", LEFT(I35,5)="VFA01"), K35="2024-02-16 14:03:02 JST Java6"), "o", IF(AND(J35="TYD01EJB.jar", K35="000000"), "o", "X6"))


=IF(AND(J35="TYD01EJB.jar", OR(LEFT(I35,5)="VEC00", LEFT(I35,5)="VEE01", LEFT(I35,5)="VFA01"), K35="2024-02-16 14:03:02 JST Java6"), "o", IF(AND(J35="TYD01EJB.jar", NOT(OR(LEFT(I35,5)="VEC00", LEFT(I35,5)="VEE01", LEFT(I35,5)="VFA01")), K35="000000"), "o", "X6"))
