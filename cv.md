# ALIAKSEI VASILYEU
### Frontend Engineer

---

### Contacts
- Phone +375-29-666-67-69
- Email: guruxhtml@gmail.com
- GitHub: [GuruHTML](https://github.com/guruhtml)

### Professional Skills Summary
- Front End software development
- Leading and mentoring skills
- High communicative and interpersonal skills
- Self-motivated

### Skills
- HTML
- CSS/SCSS
- JavaScript
- ReactJs
- Git
- Redux
- Figma
- WordPress

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

### Education
Belarusian State University of Informatics and Radioelectronics ( Computer science )

### English
- English \- A1 (Beginner)
- Russian \- Native