# Confirmation Modal Component

Confirmation modal component for React using styled-components.

## Installation

To install the package, use npm:

```bash
npm install confirmation-modal-wealth-health
```

## Usage

Exemple :
```jsx
import { useState } from 'react';
import ConfirmationModal from 'confirmation-modal-wealth-health';

function App() {
    const [showModal, setShowModal] = useState(false);

    const handleOpenModal = () => setShowModal(true);
    const handleCloseModal = () => setShowModal(false);

    return (
        <div>
            <button onClick={handleOpenModal}>Save</button>
            <ConfirmationModal
                show={showModal}
                message="Employee Created !"
                onClose={handleCloseModal}
            />
        </div>
    );
}

export default App;
```

## Props

- ``show`` : Boolean to control whether the modal is visible.
- ``message`` : Message to display inside the modal.
- ``onClose`` : Function to handle modal close event.

## Autor

Développé avec ❤️ par [Dany XIONG]([lien](https://github.com/Ekkylibre)).