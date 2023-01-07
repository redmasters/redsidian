- [x] Usar padroes de commit;
- [x] Usar gitflow;
- [x] Comitar cada arquivo alterado;
- [x] Fazer testes;
- [x] TDD;
- [x] Criar uma issue para cada feat;
- [ ] Documentar;
- [ ] Levantar Requisitos;
- [ ] Deploy na nuvem (ORACLE), usando Azure
``` 
java
@Override
public void delete(final DeletableEntity deletableEntity) {
    deletableEntity.setDeleted(true);
    deletableEntity.setDeleteDate(Instant.ofEpochMilli(clock.millis()));
    deletableEntity.setDeletedByUserUuid(currentUser.getUuid());

```
