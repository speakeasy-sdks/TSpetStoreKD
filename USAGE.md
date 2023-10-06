<!-- Start SDK Example Usage -->


```typescript
import { PetSrore } from "petStore";

(async() => {
  const sdk = new PetSrore();

  const res = await sdk.pets.createPets();

  if (res.statusCode == 200) {
    // handle response
  }
})();
```
<!-- End SDK Example Usage -->