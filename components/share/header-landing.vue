<template>
 <Navbar
  expand="lg"
  background-color="body-tertiary"
 >
  <Container type="fluid">
   <NavbarBrand >
   <b-button target="#MainNavBar" toggle="collpase">
    Navbar
   </b-button>
   </NavbarBrand>
   <NavbarToggler target="#MainNavBar" toggle="collpase" />
   <NavbarCollapse id="MainNavBar">
    <NavbarNavList>
     <NavItem>
      <NavLink
       active
       to="/"
       aria-current="page"
      >
       Home
      </NavLink>
     </NavItem>
     <NavItem>
     <NavLink to="/sample-page">Sample Page</NavLink>
     </NavItem>
     <NavItem>
      <NavLink
       disabled
       aria-current="page"
      >
       Disabled
      </NavLink>
     </NavItem>
    </NavbarNavList>
   </NavbarCollapse>
  </Container>
 </Navbar>
</template>