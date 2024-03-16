# React Native Dari Datepicker 📆

```javascript
import React from 'react';
import DatePicker from 'react-native-dari-datepicker';

const FullUsageExample = () => {
  return (
    <DatePicker
      isGregorian={false}
      options={{
        backgroundColor: '#090C08',
        textHeaderColor: '#FFA25B',
        textDefaultColor: '#F6E7C1',
        selectedTextColor: '#fff',
        mainColor: '#F4722B',
        textSecondaryColor: '#D6C7A1',
        borderColor: 'rgba(122, 146, 165, 0.1)',
      }}
      current={new Date()}
      selected={new Date()}
      mode="calendar"
      minuteInterval={30}
      style={{ borderRadius: 10 }}
    />
  );
};

```