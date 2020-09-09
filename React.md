Formik - setFieldTouched running one step behind setFieldValue. The solution run setFieldTouched in a setTimeout(() => setFieldTouched('somField', true))
