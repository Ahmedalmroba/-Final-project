ذواق هو منصة إلكترونية لتقييم المطاعم والمقاهي، وتضم ثلاثة أنواع من المستخدمين. النوع الأول هو مدير المتجر، سواء كان مطعمًا أو مقهى، وهو المسؤول عن إدارة بيانات المتجر من خلال إضافة قوائم الطعام والفروع وكل التفاصيل ذات الصلة. تُتاح الخدمات للمدير بعد مراجعة البيانات والتحقق منها. النوع الثاني هو الخبير، الذي يمكنه تقديم المراجعات والتقييمات للمتاجر، بالإضافة إلى استقبال طلبات المراجعة من المتاجر والتي يمكنه قبولها أو رفضها. تُعد مراجعات الخبراء أكثر مصداقية وتظهر في قوائم خاصة مخصصة لهم.

النوع الثالث من المستخدمين هو العميل، الذي يمكنه عرض جميع تقييمات المتاجر سواء من الخبراء أو العملاء الآخرين. يمكن للعملاء أيضًا تقييم المطاعم بناءً على تجربتهم، وتقييم النظافة، والخدمة، والجودة، والتكلفة. بالإضافة إلى ذلك، يمكنهم "الإعجاب" بأي منتج من قائمة الطعام أثناء تقديمهم للمراجعة.

لضمان أن يجد العملاء أفضل المتاجر التي تناسب تفضيلاتهم، توفر المنصة أكثر من 30 خيارًا للتصفية لتصفح المتاجر. يعتبر الموقع موثوقًا للغاية، حيث لا يمكن للخبراء تقديم المراجعات أو قبول الطلبات دون التحقق المسبق من خبراتهم ومعرفتهم. علاوة على ذلك، تتضمن المنصة نظام توصيات للعملاء يقترح المنتجات بناءً على تفضيلاتهم.

من الناحية التقنية، تم بناء المنصة باستخدام إطار عمل Spring Boot، وهي متصلة بقاعدة بيانات MySQL. تم تأمينها بفعالية واختبارها بشكل شامل لضمان الجودة.

يتكون النظام من 12 كيانًا، بما في ذلك أربعة أنواع من المستخدمين، ويحتوي على أكثر من 100 نقطة نهاية لخدمة المستخدمين وضمان تلبية جميع المتطلبات بشكل شامل.


Thawaq is an online platform for rating restaurants and cafes.
It features three types of users. The first is the admin of the store,
whether it is a restaurant or a café, responsible for managing store data by adding menus, branches, and all relevant details.
Services are made available to the admin after the data is reviewed and verified. The second user is the expert, who can provide reviews and ratings for stores,
as well as receive review requests from stores, which they can either accept or decline.
Expert reviews are more credible and appear in special lists dedicated to expert reviewers.

The third type of user is the customer, who can view all store ratings,
whether from experts or other customers. Customers can also rate the restaurant based on their experience,
evaluating cleanliness, service, quality, and cost. Additionally, they can "like" any product from the restaurant's menu that they are reviewing.

To ensure that customers find the best possible stores based on their preferences, the platform offers more than 30 filtering options for browsing stores
. The site is highly reliable, as experts cannot provide reviews or accept requests without prior verification of their expertise and knowledge. Moreover, 
the platform includes a recommendation system for customers, suggesting products based on their preferences.
From a technical perspective, the platform has been built using the Spring Boot framework, connected to a MySQL database.
It has been effectively secured and thoroughly tested to ensure quality.

The system comprises a total of 12 entities, including four types of users,
and features more than 100 endpoints to serve users and ensure that all requirements are met comprehensively.




 usecase:![image](https://github.com/user-attachments/assets/cd548f16-0d51-4e19-9422-50b41c9e9ce5)
 
class ![image](https://github.com/user-attachments/assets/9f814bca-90fd-40d9-a849-f5b1bd780714)

 https://www.figma.com/design/1CZxolWa71YlKEo5zow0jI/Thawaq?node-id=36-410&node-type=frame&t=rsD1rcMP13thcSBd-0
 
https://documenter.getpostman.com/view/37199310/2sAXqqchcn

https://documenter.getpostman.com/view/37199310/2sAXqqchcn


I wrote: Category,Menu , Favorite with CRUD and relation. Endpoint : BlockExpert,
UnblockExpert, blockStore,  unBlockStore
, CalculateAverageRatingExpert, CalculateAverageStore
,getLowestCostForCafesByName
,getLowestCostRestaurantsByName,getLowestCostForBothByName
, getLowestCostForCafesByDishType ,getLowestCostForRestaurantByDishType,
getLowestCostForBothByDishType,getLowestCostForCafesByCity,
getLowestCostForRestaurantByCity, getLowestCostForBothByCity



![صورة واتساب بتاريخ 1446-03-14 في 18 07 24_80445dab](https://github.com/user-attachments/assets/607ea62e-d6b0-4a89-9e45-ccb6e9378e78)

![صورة واتساب بتاريخ 1446-03-14 في 18 07 24_80445dab](https://github.com/user-attachments/assets/41e66dfd-506c-43c8-8efc-1f75e4aa3c90)

