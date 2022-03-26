# ALIAKSEI VASILYEU
### Frontend Engineer

---

### Skills
- HTML
- CSS/SCSS
- JavaScript
- ReactJs
- Git

### Contacts
- Phone +375-29-666-67-69
- Email: guruxhtml@gmail.com
- GitHub: [GuruHTML](https://github.com/guruhtml)



### Code Example

```javascript
import { useEffect, useState } from 'react';

const useScroll = (): number => {
  const [scrollY, setScrollY] = useState(0);

  useEffect(() => {
    const updatePosition = () => {
      setScrollY(window.pageYOffset);
    };
    window.addEventListener('scroll', updatePosition);
    updatePosition();
    return () => window.removeEventListener('scroll', updatePosition);
  }, []);

  return scrollY;
};

export default useScroll;
```


### English
- English \- A1 (Beginner)
- Russian \- Native